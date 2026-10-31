<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1e1tuxsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1e1tuxsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-candlestick-gloss" /></template>
