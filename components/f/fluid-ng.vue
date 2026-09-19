<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzfxpey5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fluid-ng" /></template>
<style>
.qzfxpey5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.162 26.96H17.108a8.27 8.27 0 0 0-8.27 8.27h0a8.27 8.27 0 0 0 8.27 8.27h22.054m-19.324-39h8.324a11 11 0 0 1 11 11v5.54h0H8.838h0V15.5a11 11 0 0 1 11-11");
}

</style>
