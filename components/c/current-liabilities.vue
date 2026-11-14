<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jk9tubb2w"/><path class="qd1t0s65l"/><path class="j3ko62yoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:current-liabilities" /></template>
<style>
.j3ko62yoe {
  d: path("M3 7.75a6.5 2 0 0 0 13 0M3 11q0 .049.008.098t.023.098t.039.097t.055.097t.07.096t.085.095t.1.093t.115.091t.129.09t.144.088q.075.043.157.085t.17.083q.089.041.184.08q.095.04.196.078t.209.074t.22.071t.231.068t.241.064t.252.06t.261.057q.132.027.269.052q.137.026.278.049t.285.044t.292.04t.297.035q.15.017.303.031t.308.026t.311.022q.156.009.314.016t.317.012l.318.008Q9.34 13 9.5 13q1.402 0 2.68-.178m.505-.079q.708-.122 1.296-.294m1.621-.76Q16 11.355 16 11m-1 4.5h6v5.75h-6Zm0 2.25h6m-4.25-3.25V16m2.5-1.5V16");
}

.jk9tubb2w {
  d: path("M3 4.5a6.5 2 0 1 0 13 0a6.5 2 0 1 0-13 0Z");
}

.qd1t0s65l {
  d: path("M3 4.5v9.75q0 .049.008.098t.023.098t.039.097t.055.097t.07.096t.085.095t.1.093t.115.091t.129.09t.144.088q.075.043.157.085t.17.083q.089.041.184.08q.095.04.196.078t.209.074t.22.071t.231.068t.241.064t.252.06t.261.057q.132.027.269.052q.137.026.278.049t.285.044t.292.04t.297.035q.15.017.303.031t.308.026t.311.022t.314.016t.317.012l.318.008q.159.002.319.002q1.432 0 2.731-.185M16 11.71V4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
