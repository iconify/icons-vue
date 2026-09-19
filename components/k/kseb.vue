<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uuu5jub6c"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kseb" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.uuu5jub6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.942 19.571v8.852m4.758 0l-3.641-4.426l3.641-4.396m-3.641 4.396H8.942m7.998 3.456c.542.707 1.223.97 2.17.97h1.31c1.22 0 2.209-.989 2.209-2.208v-.01c0-1.22-.989-2.208-2.208-2.208h-1.446a2.21 2.21 0 0 1-2.21-2.21h0c0-1.224.991-2.216 2.215-2.216h1.303c.947 0 1.628.263 2.17.97m3.238 3.456h2.886m1.54 4.426h-4.426v-8.852h4.426m6.715 4.426a2.213 2.213 0 0 1 0 4.426h-3.651V19.57h3.651a2.213 2.213 0 0 1 0 4.426m0 .001h-3.651");
}

</style>
