<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj665y5jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fj665y5jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:login-outline" /></template>
