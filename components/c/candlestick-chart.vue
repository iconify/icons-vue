<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqcne8d0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqcne8d0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:candlestick-chart" /></template>
