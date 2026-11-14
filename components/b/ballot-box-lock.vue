<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="as6ts1jvf"/><path class="pejtcgqnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ballot-box-lock" /></template>
<style>
.as6ts1jvf {
  d: path("M12.215 20.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 17v-3.5q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 10h9.5q.133 0 .266.01t.265.03q.132.021.261.051q.13.03.257.07q.128.04.251.09q.124.049.244.108q.119.059.234.126q.115.068.224.144q.11.077.213.161t.199.176q.097.092.186.191t.171.205q.081.105.154.217q.074.111.138.228q.065.116.12.238t.101.246M7.5 10V3.5H14V10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pejtcgqnb {
  d: path("m9.25 7l1.25 1.25l2-2.25m4.25 11.5h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
