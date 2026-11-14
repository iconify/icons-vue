<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mmnv1cbvr"/><path class="vyfae_dkn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:accountant-badge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mmnv1cbvr {
  d: path("M13.168 18.799Q12.601 19 12 19H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 15.5V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 2.5h6q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T15.5 6v4.242");
}

.vyfae_dkn {
  d: path("M7.25 5.5h3.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 10.75 9h-3.5A1.75 1.75 0 0 1 5.5 7.25A1.75 1.75 0 0 1 7.25 5.5m-.75 7h.01m3.99 0h.01M6.5 16h.01m3.99 0h.01m4.49-.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m1.25 2.5l-.75 3.5m4.25-3.5l.75 3.5");
}

</style>
