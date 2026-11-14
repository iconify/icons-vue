<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kso5zvmkb"/><path class="ard30xbve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crime-scene-lab" /></template>
<style>
.ard30xbve {
  d: path("M17.25 21.5v-3a1 1 0 0 1 2 0V20");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kso5zvmkb {
  d: path("M6.25 2.5h.5A1.75 1.75 0 0 1 8.5 4.25v5A1.75 1.75 0 0 1 6.75 11h-.5A1.75 1.75 0 0 1 4.5 9.25v-5A1.75 1.75 0 0 1 6.25 2.5M8.5 5H10q.135 0 .27.007q.135.006.269.019q.134.014.268.034q.134.019.266.046q.132.026.263.059t.261.072t.256.085q.127.045.252.097q.124.051.247.109q.122.058.241.121q.119.064.235.133q.115.07.228.145q.112.075.22.155q.109.081.213.166q.105.086.205.177q.1.09.195.186q.096.095.186.195q.091.1.177.205t.166.213t.155.22q.075.113.145.228q.069.116.133.235q.063.119.121.241q.058.123.109.247q.052.125.097.252t.085.256q.039.13.072.261t.059.263t.046.266t.034.268q.013.134.019.269q.007.135.007.27q0 .497-.089.986t-.264.953q-.176.465-.431.891q-.256.426-.584.8m-.376.388q-.379.354-.817.631t-.92.467t-.992.287T10 16v5m-7-7h11.25M3.5 21h8.75m2.75.5v-3a3.25 3.25 0 0 1 6.5 0v3");
}

</style>
