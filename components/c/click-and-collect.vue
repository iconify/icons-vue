<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vkms8k44g"/><path class="jkln-dbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:click-and-collect" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkln-dbhb {
  d: path("M14 15.923v4.072a.676.676 0 0 0 1.125.505l.035-.032a1.21 1.21 0 0 1 1.84.282l.232.386a1.03 1.03 0 0 0 1.393.364a.94.94 0 0 0 .316-1.339l-.191-.286a.798.798 0 0 1 .597-1.237l.153-.013a.611.611 0 0 0 .337-1.08l-3.385-2.781A1.5 1.5 0 0 0 14 15.923");
}

.vkms8k44g {
  d: path("M11.215 19.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 16V7q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 3.5h10q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T19.5 7v6.642M9 3.5V9m4-5.5V9");
}

</style>
