<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gy2xqhf_n"/><circle class="zplh2gsjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doctor-care-anywhere" /></template>
<style>
.gy2xqhf_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.268 45.406c-2.001 0-4.01-.288-5.97-.857a4.5 4.5 0 0 1-3.066-5.576a4.5 4.5 0 0 1 5.577-3.067c1.143.332 2.307.5 3.459.5c6.84 0 12.406-5.565 12.406-12.406s-5.566-12.406-12.406-12.406S11.86 17.159 11.86 24c0 1.385.244 2.773.723 4.129A4.5 4.5 0 0 1 4.1 31.13A21.3 21.3 0 0 1 2.86 24c0-11.804 9.603-21.406 21.407-21.406S45.674 12.196 45.674 24S36.07 45.406 24.268 45.406");
}

.zplh2gsjk {
  cx: 24.268px;
  cy: 24px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
