<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_3w9wbid"/><path class="dap-qtjaa"/><circle class="cpk0fnbgt"/><ellipse class="me3tgdb5c"/><ellipse class="u-rbut60m"/><ellipse class="l-_0f0bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drive-safe-save" /></template>
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

.dap-qtjaa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.856 30.967l7.767.047c-.216-5.361-.456-9.093 3.691-13.568s14.252-6.28 14.336-8.486S21.883 6.722 18 5.508c3.092.311 13.027.638 16.743 2.193c1.586.828 1.148 1.895.591 2.707c-1.621 2.276-8.99 6.623-8.321 10.25c.594 4.402 5.459 7.074 9.205 10.356h8.007");
}

.g_3w9wbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.763 30.95c.011-.847-3.201-3.1-3.696-8.577S31.431 11.676 32.407 9.76S28.7 7.623 27.118 6.606");
}

.l-_0f0bxa {
  cx: 20.387px;
  cy: 39.573px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.525px;
  ry: 2.368px;
}

.me3tgdb5c {
  cx: 24px;
  cy: 35.325px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.525px;
  ry: 2.368px;
}

.u-rbut60m {
  cx: 27.613px;
  cy: 39.592px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.525px;
  ry: 2.368px;
}

</style>
