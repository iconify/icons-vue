<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrlt70_9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrlt70_9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cake-3-fill" /></template>
