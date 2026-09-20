<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbmv8abrr"/><path class="wknwzugnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eg-payment" /></template>
<style>
.jbmv8abrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.5 5.5h-25a2 2 0 0 0-2 2v25c0 5.523 4.477 10 10 10h25a2 2 0 0 0 2-2v-25c0-5.523-4.477-10-10-10m-18 15.125h5.401");
}

.wknwzugnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.251 27.375H14.5V13.874h6.751M33.5 25.097a4.472 4.472 0 0 0-8.945 0v4.557a4.472 4.472 0 0 0 8.945 0h-4.472");
}

</style>
