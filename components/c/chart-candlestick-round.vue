<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_i7jf3cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_i7jf3cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-candlestick-round" /></template>
