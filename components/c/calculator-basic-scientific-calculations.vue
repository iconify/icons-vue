<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tsxiyvl5g"/><path class="b j8cfydbjf"/><path class="oez4xub5u"/><path class="b hq2hh0oqt"/><path class="u2f7gi_hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calculator-basic-scientific-calculations" /></template>
<style>
.hq2hh0oqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.67 27.252c.5.6 1.1.9 2 .9h1.2c1.1 0 2-.9 2-2s-.9-2-2-2h-1.3c-1.1 0-2-.9-2-2s.9-2 2-2h1.2c.9 0 1.5.2 2 .9m-2.6-.9v-1m0 10v-1");
}

.j8cfydbjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.253 27c-.5.6-1.2 1-2.1 1c-1.5 0-2.7-1.2-2.7-2.7v-2.6c0-1.5 1.2-2.7 2.7-2.7c.8 0 1.6.4 2.1 1m-6 1.9h3.4m-3.4 2h3.4");
}

.oez4xub5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.181 33.395h4M22 12.402h4m-2-2v4");
}

.tsxiyvl5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m2.84 1.186L6.744 41.15m0-34.464L41.34 41.339");
}

.u2f7gi_hn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.181 35.757h4");
}

</style>
