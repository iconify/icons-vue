<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeeth69mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeeth69mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:candlestick" /></template>
