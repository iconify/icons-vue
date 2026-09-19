<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="knz7amwcr"/><path class="ay8ds1bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:expenses" /></template>
<style>
.ay8ds1bzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.329 39.233a2.382 2.382 0 1 0 2.911 3.77h0a8.575 8.575 0 0 0-.574-13.981c6.525-2.577 9.726-9.956 7.15-16.481c-2.578-6.526-9.956-9.727-16.482-7.15s-9.726 9.956-7.15 16.481a12.7 12.7 0 0 0 7.15 7.15a8.575 8.575 0 0 0-.574 13.981a2.382 2.382 0 0 0 2.911-3.77a3.81 3.81 0 1 1 4.658 0");
}

.knz7amwcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.492 20.36a1.906 1.906 0 0 0 2.367 2.986a7.834 7.834 0 1 0-9.73 0a1.905 1.905 0 0 0 2.367-2.987a4.023 4.023 0 1 1 4.996 0");
}

</style>
