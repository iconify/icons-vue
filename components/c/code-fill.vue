<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy66ctbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wy66ctbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:code-fill" /></template>
