<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pqk2ys7tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:image-compressor" /></template>
<style>
.pqk2ys7tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.057 21.99V8.674M7.74 21.99h13.316L5.5 6.433m20.51 14.624h13.316M26.01 7.74v13.316L41.567 5.5M21.99 26.943v13.316M8.674 26.943H21.99L6.433 42.5m20.51-16.49h13.316M26.943 39.325V26.01L42.5 41.566");
}

</style>
