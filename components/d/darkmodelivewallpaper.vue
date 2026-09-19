<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xbj9ovgaw"/><circle class="d484i646s"/><path class="i3kdfpbjs"/><circle class="qna8z_b-k"/><circle class="xlammgm7j"/><path class="ogaqwi_jy"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:darkmodelivewallpaper" /></template>
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

.d484i646s {
  cx: 13.419px;
  cy: 15.733px;
  r: 3.578px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i3kdfpbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.94 12.254l-.915-.916m8.789 8.79l-.916-.916m-3.478-8.398V9.518m0 12.43v-1.296m4.919-4.919h1.296m-12.431 0H8.5m8.398-3.479l.916-.916m-8.789 8.79l.916-.916m25.167-7.708l-.069.005a4.225 4.225 0 0 1-2.88 7.24a4.225 4.225 0 1 0 2.949-7.246Z");
}

.ogaqwi_jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 11.974l10.092 23.504l2.033-6.315l4.302 8.567M24 45.406V11.974");
}

.qna8z_b-k {
  cx: 31.117px;
  cy: 12.443px;
  r: 0.333px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xbj9ovgaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.974L13.908 35.478l-2.033-6.315l-4.365 8.692");
}

.xlammgm7j {
  cx: 32.005px;
  cy: 16.319px;
  r: 0.333px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
