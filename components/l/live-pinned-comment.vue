<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fi69-lbkt"/><path class="jp5qhwnar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-pinned-comment" /></template>
<style>
.fi69-lbkt {
  d: path("M19 9.642V13.5q0 .172-.017.343t-.05.34q-.034.168-.084.333t-.115.323q-.066.159-.147.311t-.177.294t-.204.276q-.11.133-.231.255q-.122.121-.255.231q-.133.109-.276.204q-.142.096-.294.177t-.311.147t-.323.115t-.333.084q-.169.033-.34.05T15.5 17H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 13.5V9q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 5.5 6 5.5h8.4M6 20.5h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jp5qhwnar {
  d: path("M7.5 11.108v.284a1.307 1.307 0 0 0 2 1.108a1.474 1.474 0 0 0 0-2.5a1.307 1.307 0 0 0-2 1.108M15 9l2.75-2.75a2.125 2.125 0 1 1 3 0a2.125 2.125 0 0 1-3 0");
}

</style>
