<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="lu4vk7b_u"/><path class="jl8at1e8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:324" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jl8at1e8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.614 19.835c.691-.576 1.437-.84 3.111-.835l.39.002a2.5 2.5 0 0 1 2.499 2.5h0a2.5 2.5 0 0 1-2.5 2.5m-1.921-.001h1.921");
}

.lu4vk7b_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.129 29l-.001-10l-5.367 6.717h6.625M20.83 22.313a3.316 3.316 0 0 1 3.97-3.25c1.39.267 2.499 1.469 2.637 2.876c.103 1.048-.228 2.081-.952 2.716C25.145 25.83 20.831 29 20.831 29h6.625m-14.841-.843c.69.578 1.435.843 3.11.843h.39a2.5 2.5 0 0 0 2.499-2.5h0a2.5 2.5 0 0 0-2.5-2.499");
}

</style>
