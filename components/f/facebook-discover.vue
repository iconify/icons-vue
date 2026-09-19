<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="kqp07hbkl"/><path class="w2qn22h5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:facebook-discover" /></template>
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

.kqp07hbkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.286 30.919h-9.233V13.597h9.233a8.66 8.66 0 0 1 8.661 8.66h0a8.66 8.66 0 0 1-8.66 8.662");
}

.w2qn22h5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.053 14.216c13.914 9.144 10.76 20.705 8.624 21.913c-2.475 1.401-8.198-2.918-8.624-5.21");
}

</style>
