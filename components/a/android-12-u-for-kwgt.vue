<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><rect class="yi_-_1bee"/><path class="ev-agq82t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:android-12-u-for-kwgt" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ev-agq82t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.786 27.358h-.27a2.16 2.16 0 0 0-2.161 2.162h0v1.434a.27.27 0 0 1-.089.2l-2.443 2.221a.54.54 0 0 0-.036.763q.017.02.036.037l2.443 2.22a.27.27 0 0 1 .089.2v1.435a2.16 2.16 0 0 0 2.16 2.16h.27a.27.27 0 0 0 .27-.27v-4.301a.54.54 0 0 0-.158-.382l-1.271-1.272a.27.27 0 0 1 0-.382l1.271-1.271a.54.54 0 0 0 .159-.382v-4.301a.27.27 0 0 0-.27-.27ZM13.5 24.497h8.206M13.5 10.281l4.103-2.266m0 0v16.482m6.024-11.124a5.49 5.49 0 0 1 5.334-5.563a5.66 5.66 0 0 1 5.539 5.563a5.64 5.64 0 0 1-1.641 3.914c-2.257 1.854-9.232 7.21-9.232 7.21H34.5");
}

.yi_-_1bee {
  width: 2.701px;
  height: 12.831px;
  x: 19.945px;
  y: 27.358px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.54px;
}

</style>
