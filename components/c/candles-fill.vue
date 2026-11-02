<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siy5ylbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siy5ylbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candles-fill" /></template>
