<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axgcsddwl"/><path class="ulgm-nb-m"/><path class="wj_0xshzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:listener-mail" /></template>
<style>
.axgcsddwl {
  d: path("M12.315 16H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 12.5v-5q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 4 6 4h10q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v4.542");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ulgm-nb-m {
  d: path("m2.5 6.5l8.5 5l8.5-5m-4.75 15v-3.25a3.5 3.5 0 0 1 7 0v3.25");
}

.wj_0xshzv {
  d: path("M15 18.5za1 1 0 0 1 1 1v1.25a1 1 0 0 1-1 1a1 1 0 0 1-1-1V19.5a1 1 0 0 1 1-1m6 0za1 1 0 0 1 1 1v1.25a1 1 0 0 1-1 1a1 1 0 0 1-1-1V19.5a1 1 0 0 1 1-1");
}

</style>
