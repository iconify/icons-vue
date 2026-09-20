<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh_3qzbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zh_3qzbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:ff" /></template>
