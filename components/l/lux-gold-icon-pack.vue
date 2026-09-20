<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mxvep0bec"/><path class="ch7ci28fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lux-gold-icon-pack" /></template>
<style>
.ch7ci28fu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 5.5za5 5 0 0 1 5 5V24a5 5 0 0 1-10 0V10.5a5 5 0 0 1 5-5");
}

.mxvep0bec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 5.5za5 5 0 0 1 5 5v27a5 5 0 0 1-10 0v-27a5 5 0 0 1 5-5m8.5 32v-27c0-2.77 2.23-5 5-5s5 2.23 5 5v22h8.5c2.77 0 5 2.23 5 5s-2.23 5-5 5H24c-2.77 0-5-2.23-5-5");
}

</style>
