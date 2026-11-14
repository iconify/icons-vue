<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hs8gqob5n"/><path class="il6-zua0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:appointment-office" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hs8gqob5n {
  d: path("M11.715 19.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 16V8q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 4.5 6 4.5h9q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T18.5 8v3.742M7 2.5v4m7-4v4");
}

.il6-zua0r {
  d: path("M7.75 9.5h.5A1.75 1.75 0 0 1 10 11.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 6 11.75v-.5A1.75 1.75 0 0 1 7.75 9.5m8.5 7h4A1.75 1.75 0 0 1 22 18.25v2A1.75 1.75 0 0 1 20.25 22h-4a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75m.25 0v-1a1 1 0 0 1 1-1H19a1 1 0 0 1 1 1v1");
}

</style>
