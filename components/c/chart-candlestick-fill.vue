<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckohrz7gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckohrz7gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:chart-candlestick-fill" /></template>
