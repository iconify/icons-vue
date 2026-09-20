<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ir2z49b3i"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:echo" /></template>
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

.ir2z49b3i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.84 2.75a153 153 0 0 0-1.79 17.88a69 69 0 0 1 7.46-.6h2.36l-.48 2.32c-.2 1-.29 1.27-.49 2.1a39 39 0 0 1 4.8.61l2.37.68l-1.2 2.15c-3.13 5.63-8.73 8-10.69 8.72A73 73 0 0 0 24.32 44c.12.57.21 1 .32 1.5M28.58 8a3.69 3.69 0 0 1 0 7.37a3.69 3.69 0 0 1-3.69-3.69A3.69 3.69 0 0 1 28.58 8");
}

</style>
