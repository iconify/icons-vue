<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j0x0p8bca"/><path class="tduxbjb9y"/><path class="lmbtqi-8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:libby" /></template>
<style>
.j0x0p8bca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.85 14.43l-15.42 3.64a1.8 1.8 0 0 1-.86 0L8.15 14.43a1.87 1.87 0 0 0-1.87 1.86V38a1.87 1.87 0 0 0 1.87 1.86l15.42 3.62a1.8 1.8 0 0 0 .86 0l15.42-3.62A1.87 1.87 0 0 0 41.72 38V16.29a1.87 1.87 0 0 0-1.87-1.86m-17.28 3.41v25.37m2.86-25.37v25.37");
}

.lmbtqi-8s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.17 7.82V4.5l2.53 1.63l2.53-1.63v7.02");
}

.tduxbjb9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.56 15a15.1 15.1 0 0 0-27.12 0");
}

</style>
