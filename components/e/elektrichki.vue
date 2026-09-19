<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j8jg-ob5f"/><path class="kav8xqbqa"/><circle class="u7xelli0s"/><circle class="ntp77mbgr"/><path class="b7ellfvow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:elektrichki" /></template>
<style>
.b7ellfvow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.521 4.5H31.48m-4.118 0v3.379M20.638 4.5v3.379");
}

.j8jg-ob5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.456 7.879h21.089a2.48 2.48 0 0 1 2.482 2.473V34.57a2.48 2.48 0 0 1-2.472 2.484h-21.1a2.48 2.48 0 0 1-2.482-2.474V10.363a2.48 2.48 0 0 1 2.471-2.484Zm2.615 32.401H31.93M14.27 43.5l3.604-6.447m12.25 0l3.604 6.447");
}

.kav8xqbqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.01 7.879h19.979v15.464H14.01z");
}

.ntp77mbgr {
  cx: 31.929px;
  cy: 32.462px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u7xelli0s {
  cx: 16.071px;
  cy: 32.462px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
