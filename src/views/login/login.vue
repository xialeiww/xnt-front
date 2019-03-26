<template>
    <div id="login">
        <form action="">
            <label for="username">用户名：</label>
            <input type="text" name="username" v-model="username">
            <label for="password">密码：</label>
            <input type="text" name="password" v-model="password">
            <input type="button" value="提交" @click.prevent="subm">
        </form>
    </div>
</template>
<script>
export default {
    name:'login',
    data(){
        return {
            username: '',
            password:''
        }
    },
    methods:{
        subm(){
            console.log("提交")
        }
    }
}
</script>
<style>
    
</style>