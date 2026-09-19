<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frhjjwbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="frhjjwbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:line-chart" /></template>
