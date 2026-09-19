<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o20yp87lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o20yp87lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:code-outlined" /></template>
