<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g-8g8_b-y"/><circle class="uk-8h_hlj"/><path class="cfziknqsa"/><ellipse class="czdyafgvs"/><path class="jiysjjbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dnsfilter" /></template>
<style>
.cfziknqsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.38 29.25A17 17 0 0 0 24 27.31a17 17 0 0 0-8.38 1.94m0-14.25A17 17 0 0 0 24 17a17 17 0 0 0 8.38-2");
}

.czdyafgvs {
  cx: 24px;
  cy: 22.14px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.07px;
  ry: 11px;
}

.g-8g8_b-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5s-11.26 2-15.25 2v20a11.2 11.2 0 0 0 .8 4.1a15 15 0 0 0 2 3.61a22 22 0 0 0 2.81 3.07a35 35 0 0 0 3 2.48a34 34 0 0 0 2.89 1.86c1 .59 1.71 1 2.13 1.19l1 .49a1.44 1.44 0 0 0 1.24 0l1-.49c.42-.2 1.13-.6 2.13-1.19a34 34 0 0 0 2.89-1.86a35 35 0 0 0 3-2.48a22 22 0 0 0 2.81-3.07a15 15 0 0 0 2-3.61a11.2 11.2 0 0 0 .8-4.1v-20c-3.99.03-15.25-2-15.25-2");
}

.jiysjjbfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11.14v22m-11-11h22");
}

.uk-8h_hlj {
  cx: 24px;
  cy: 22.14px;
  r: 11px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
