<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m64gr6bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m64gr6bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:box-plot-outline" /></template>
