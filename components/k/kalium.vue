<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ep_t-3b7h"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kalium" /></template>
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

.ep_t-3b7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 21.3c-1.187 3.442-4.349 7.197-7.919 8.053c-3.661.878-7.591-3.116-10.117-5.054M11 26.7c1.187-3.443 4.349-7.197 7.919-8.053c3.66-.878 7.591 3.116 10.117 5.053");
}

</style>
