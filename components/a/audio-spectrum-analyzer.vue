<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g-frixucj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audio-spectrum-analyzer" /></template>
<style>
.g-frixucj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 25.018h9.877l2.277-10.973l2.278 20.162l2.277-25.145l2.278 29.876l2.277-29.745l2.278 27.235l2.277-25.406l2.278 18.756l2.277-16.217l2.278 11.363H44.5");
}

</style>
