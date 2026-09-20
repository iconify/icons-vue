<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd-ouuhoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:candlestick-chart-outline" /></template>
<style>
.nd-ouuhoi {
  fill: currentColor;
  d: path("M7 20v-2H5V6h2V4h2v2h2v12H9v2zm0-4h2V8H7zm8 4v-5h-2V8h2V4h2v4h2v7h-2v5zm0-7h2v-3h-2zm1-1.5");
}

</style>
