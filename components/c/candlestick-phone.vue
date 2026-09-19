<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co3vs6bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co3vs6bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:candlestick-phone" /></template>
