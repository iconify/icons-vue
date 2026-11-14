<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t2rc-xkml"/><path class="jvpkw3bol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:epic-at-risk" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jvpkw3bol {
  d: path("M6.5 9V5.5a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H18m1.074 4.732l1.5 2.812a1.5 1.5 0 0 1-1.324 2.206h-3a1.5 1.5 0 0 1-1.324-2.206l1.5-2.812a1.5 1.5 0 0 1 2.648 0m-1.324.518V18m0 1.75h.01");
}

.t2rc-xkml {
  d: path("M11.915 20H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 16.5v-4q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 9h8.5q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311t.115.323t.084.333q.033.169.05.34T18 12.5v.142");
}

</style>
