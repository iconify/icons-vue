<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxl1c6bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxl1c6bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bell-electric-line" /></template>
