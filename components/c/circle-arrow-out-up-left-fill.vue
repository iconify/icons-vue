<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh88yn8ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zh88yn8ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-arrow-out-up-left-fill" /></template>
