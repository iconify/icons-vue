<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g42bubbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g42bubbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:close" /></template>
