<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w94crya9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w94crya9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-candlestick-solid" /></template>
