<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="lf-1-qymy"/><path class="n8qxx0btl"/><path class="gn1eucc0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epson-print-enabler" /></template>
<style>
.gn1eucc0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.601 32.727h-.862v-4.505h-4.505v-.878a2.634 2.634 0 1 0-5.269 0v.878H23.46v4.505h.863a2.634 2.634 0 1 1 0 5.268h-.863V42.5h4.505v-.878a2.634 2.634 0 1 1 5.269 0v.878h4.505v-4.505h.862a2.634 2.634 0 1 0 0-5.268");
}

.lf-1-qymy {
  width: 26.341px;
  height: 10.27px;
  x: 6.765px;
  y: 11.62px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.536px;
  ry: 1.536px;
}

.n8qxx0btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.983 23.246v-1.355H11.887v9.318c0 .848.688 1.536 1.536 1.536h7.403M13.423 5.5h13.024c.848 0 1.536.688 1.536 1.536v4.585H11.887V7.036c0-.848.688-1.536 1.536-1.536m2.162 20.244h8.7m-8.7 3.871h5.188");
}

</style>
