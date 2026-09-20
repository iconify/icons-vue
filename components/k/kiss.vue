<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_sr8q0id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kiss" /></template>
<style>
.o_sr8q0id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.5 21.5 0 1 0 45.5 24A21.51 21.51 0 0 0 24 2.5m0 5.22c8.53 0 16.28 7.76 16.28 16.28S32.52 40.28 24 40.28S7.72 32.52 7.72 24S15.47 7.72 24 7.72");
}

</style>
