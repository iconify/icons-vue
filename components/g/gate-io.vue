<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cyl411b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gate-io" /></template>
<style>
.cyl411b8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 24h9.5A21.499 21.499 0 0 1 8.798 39.202A21.5 21.5 0 0 1 24 2.5V24zV12H24a12.001 12.001 0 0 0-8.485 20.485A12 12 0 0 0 35.999 24");
}

</style>
