<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cwu77bbvh"/><path class="gczsc8bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-utilities" /></template>
<style>
.cwu77bbvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.678 13.044H24.77c-1.963-.108-5.931-4.238-8.188-4.238H6.68v-.001a2.176 2.176 0 0 0-2.18 2.171v7.307h39v-3.418a1.822 1.822 0 0 0-1.822-1.821Zm1.822 5.239h-39v18.733a2.176 2.176 0 0 0 2.174 2.18h34.645a2.176 2.176 0 0 0 2.181-2.172V18.283Z");
}

.gczsc8bcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.278 25.858l1.8 1.471l2.175-.823l.374-2.295l-1.8-1.472m6.891 8.233l-5.465-4.466m9.44 5.114l-1.801-1.471l-2.174.823l-.374 2.295l1.8 1.472");
}

</style>
