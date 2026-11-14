<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z4m7w_beb"/><path class="q18eu5bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loan-interest-certificate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q18eu5bhz {
  d: path("M14 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M15 21l5.25-5.25m-4-.25h4.25v4.25");
}

.z4m7w_beb {
  d: path("M13.915 17H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 13.5v-6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 4 6 4h12q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34t.017.343v5.342M6 13.5l5-6m-4.5.75h.01m3.99 4.5h.01");
}

</style>
