<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm2fqkhii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm2fqkhii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-candlestick-line" /></template>
