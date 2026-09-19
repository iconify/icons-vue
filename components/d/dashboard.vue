<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi3d-wbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hi3d-wbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:dashboard" /></template>
