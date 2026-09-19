<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="edi79mb8h"/><circle class="swi8cjb6o"/><circle class="t7dnz0v3k"/><circle class="h8fcfbbbf"/><circle class="gd6crfboq"/><circle class="zlslg69-k"/><circle class="o0bnrybos"/><path class="fbelz358i"/><path class="sneajcbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fing" /></template>
<style>
.edi79mb8h {
  cx: 24px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fbelz358i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.484 41.918a18.15 18.15 0 0 0 6.721-2.786m-20.41 0a18.15 18.15 0 0 0 6.72 2.786M6.085 27.499a18.15 18.15 0 0 0 2.783 6.706M8.86 13.807a18.15 18.15 0 0 0-2.775 6.694M20.5 6.085a18.15 18.15 0 0 0-6.693 2.775m25.807 5.687A18.27 18.27 0 0 0 27.5 6.085m11.632 28.12A18.17 18.17 0 0 0 42.25 24a19 19 0 0 0-.119-2.092");
}

.gd6crfboq {
  cx: 11.272px;
  cy: 11.272px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h8fcfbbbf {
  cx: 11.272px;
  cy: 36.728px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o0bnrybos {
  cx: 6px;
  cy: 24px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sneajcbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.165 9.577l-.551 4.97l-4.969-.551");
}

.swi8cjb6o {
  cx: 24px;
  cy: 6px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t7dnz0v3k {
  cx: 24px;
  cy: 42px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zlslg69-k {
  cx: 36.728px;
  cy: 36.728px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
