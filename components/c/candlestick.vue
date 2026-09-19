<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og8m8vboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og8m8vboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:candlestick" /></template>
