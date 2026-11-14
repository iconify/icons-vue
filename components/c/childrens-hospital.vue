<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="arc3od4wo"/><path class="kptrj8i4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:childrens-hospital" /></template>
<style>
.arc3od4wo {
  d: path("M13.265 20.668q-.235.2-.502.355q-.267.156-.556.262t-.594.161q-.304.054-.613.054H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 18V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 2.5h5q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T14.5 6v8.142m0 .2V18q0 .066-.003.133");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kptrj8i4k {
  d: path("M6.75 21.5v-5h3.5v5M8.5 5.5v5M6 8h5m6.25 6.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M16 21.5c0-1.5 1.5-2.5 3.25-2.5S22 20 22 21.5");
}

</style>
