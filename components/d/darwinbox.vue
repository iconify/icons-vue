<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jnekhobuv"/><path class="gd7vd-fkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:darwinbox" /></template>
<style>
.gd7vd-fkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.528 32.759V8.866A3.366 3.366 0 0 1 32.894 5.5h.852m-4.219 17.041c0-3.306-2.704-6.01-6.01-6.01h0c-3.306 0-6.01 2.705-6.01 6.01v3.907c0 3.306 2.704 6.01 6.01 6.01h0c3.306 0 6.01-2.704 6.01-6.01");
}

.jnekhobuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.926 5.5H9.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-1.264");
}

</style>
