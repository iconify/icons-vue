<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcbwawvox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcbwawvox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:compass-2-fill" /></template>
