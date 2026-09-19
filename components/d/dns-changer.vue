<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0e0psb-q"/><circle class="dmv1fh84j"/><path class="emngd0bkq"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dns-changer" /></template>
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

.dmv1fh84j {
  cx: 30.621px;
  cy: 32.071px;
  r: 1.812px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.emngd0bkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.232 29.118a1.65 1.65 0 0 0-1.477-.67h-.134a1.805 1.805 0 0 0-1.812 1.811v1.812");
}

.h0e0psb-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.975 24.963V14.116h1.762a5.44 5.44 0 0 1 5.423 5.423h0a5.44 5.44 0 0 1-5.423 5.423Zm11.432-.001V14.117l7.186 10.845V14.117m4.383 9.625a3.23 3.23 0 0 0 2.711 1.22h1.627a2.72 2.72 0 0 0 2.711-2.711h0a2.72 2.72 0 0 0-2.711-2.711H34.55a2.72 2.72 0 0 1-2.711-2.712h0a2.72 2.72 0 0 1 2.711-2.711h1.627a2.91 2.91 0 0 1 2.712 1.22M15.567 33.883h1.611m-1.611-5.369h1.611m-.806 0v5.369m2.971 0v-5.369h1.745a1.812 1.812 0 1 1 0 3.624h-1.745m7.871-1.812l-1.343 3.557l-1.342-3.557");
}

</style>
