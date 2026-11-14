<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ej3kizbgb"/><path class="nls0jkfyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:clinical-note" /></template>
<style>
.ej3kizbgb {
  d: path("M17 15.342V18q0 .172-.017.343t-.05.34q-.034.168-.084.333t-.115.323q-.066.159-.147.311t-.177.294q-.095.143-.204.276q-.11.133-.231.255q-.122.121-.255.231q-.133.109-.276.204q-.142.096-.294.177t-.311.147t-.323.115t-.333.084q-.169.033-.34.05t-.343.017h-7q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3 18V8q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q6.328 4.5 6.5 4.5h7q.336 0 .666.064M6.5 2.5v4m3.5-4v4m3.5-4v2.9M6 10.5h3.2M6 14h1.8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nls0jkfyz {
  d: path("m19.058 5.477l.383.321a1.5 1.5 0 0 1 .185 2.114l-5.846 6.966a1.5 1.5 0 0 1-.642.448l-1.253.45a1.013 1.013 0 0 1-1.341-1.125l.226-1.312a1.5 1.5 0 0 1 .329-.71l5.846-6.967a1.5 1.5 0 0 1 2.113-.185");
}

</style>
