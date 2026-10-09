<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-p0xm3rr.css';
import '../../css/e/eb5j48vwt.css';
import '../../css/m/m3rdxrnyn.css';
import '../../css/n/ndjuxyb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-p0xm3rr"/><path class="eb5j48vwt"/><path class="m3rdxrnyn"/><path class="ndjuxyb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-candlestick-20" /></template>
