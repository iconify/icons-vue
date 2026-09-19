<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i7-n2wb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:awds" /></template>
<style>
.i7-n2wb8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24C2.5 12.126 12.126 2.5 24 2.5V24zm43 0c0 11.874-9.626 21.5-21.5 21.5V24z");
}

</style>
