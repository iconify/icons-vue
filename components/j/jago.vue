<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xd4huib0y"/><circle class="mh2jb9b-v"/><circle class="p13eqyb5z"/><circle class="t1sz91bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jago" /></template>
<style>
.mh2jb9b-v {
  cx: 14.073px;
  cy: 9.458px;
  r: 4.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p13eqyb5z {
  cx: 23.998px;
  cy: 9.458px;
  r: 4.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t1sz91bkb {
  cx: 33.927px;
  cy: 9.458px;
  r: 4.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xd4huib0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.708 20.16l.023 9.415a4.245 4.245 0 0 1-3.997 4.47c-8.177.717-3.788-9.163-10.808-8.95c-4.558.475-5.11 5.342-3.448 9.268c5.452 14.443 27.147 10.675 27.251-3.681c.077-1.048.063-10.325.063-10.325c-.145-5.15-8.907-5.25-9.084-.197");
}

</style>
