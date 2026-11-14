<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c1bjaw43e"/><path class="jf69k_jbg"/><path class="apv334bsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backlog-add" /></template>
<style>
.apv334bsw {
  d: path("M15.5 6.5v-1a2 2 0 0 0-2-2h-9a2 2 0 0 0-2 2v9h3m6-1.5H16m2 2v6m-3-3h6");
}

.c1bjaw43e {
  d: path("M13.815 20.5H12q-.172 0-.343-.017t-.34-.05q-.168-.034-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177t-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T8.5 17v-4q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294t.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084q.169-.033.34-.05T12 9.5h5.5q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311t.115.323t.084.333q.033.169.05.34T21 13v2.242");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf69k_jbg {
  d: path("M18.5 9.5v-1a2 2 0 0 0-2-2h-9a2 2 0 0 0-2 2v9h3");
}

</style>
