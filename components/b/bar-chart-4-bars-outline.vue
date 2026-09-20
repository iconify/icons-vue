<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxi4c3g8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bar-chart-4-bars-outline" /></template>
<style>
.cxi4c3g8h {
  fill: currentColor;
  d: path("M2 21v-2h20v2zm1-3v-7h3v7zm5 0V6h3v12zm5 0V9h3v9zm5 0V3h3v15z");
}

</style>
