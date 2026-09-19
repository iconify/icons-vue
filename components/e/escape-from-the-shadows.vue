<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1tf1ybqr"/><circle class="jrn_hrbzi"/><circle class="iir8xkbnf"/><path class="tzh5-xbku"/><path class="e6ehxhb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:escape-from-the-shadows" /></template>
<style>
.e6ehxhb-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.477 23.733s2.87.34 3.279-1.184m12.187 1.184s-2.87.34-3.279-1.184");
}

.iir8xkbnf {
  cx: 31.03px;
  cy: 20.511px;
  r: 1.546px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.jrn_hrbzi {
  cx: 18.763px;
  cy: 20.672px;
  r: 1.546px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.m1tf1ybqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.595 27.208c2.12 5.201 2.818 10.758 3.606 16.292c4.883-8.712 2.752-16.372.966-24.084");
}

.tzh5-xbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.227 37.019c-5.35.098-5.937-3.75-8.267-6.913c-2.908-3.95-7.298-8.522-4.83-13.33c1.613-3.14 2.532-6.495 5.078-9.436c.765-.883 2.09-1.988 3.358-2.316c2.963-.765 4.984-.595 6.541-.11c3.125.977 4.221 3.673 6.08 6.131c3.952 5.224 4.422 9.704 1.643 13.587c-3.443 4.812-4.068 7.111-5.77 10.106");
}

</style>
