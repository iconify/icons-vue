<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye-rnqb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fiber-terminal-off" /></template>
<style>
.ye-rnqb-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.581 4.568q.119-.18.26-.344q.14-.164.3-.309q.159-.146.336-.271q.176-.125.366-.227q.191-.102.392-.18t.411-.131q.209-.053.424-.079Q11.284 3 11.5 3h6q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T21 6.5v6q0 .217-.027.432t-.08.425t-.131.413t-.182.392q-.103.191-.229.368t-.272.336t-.312.301q-.165.14-.346.259M12.015 16H11.5q-.172 0-.343-.017t-.34-.05q-.168-.034-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177t-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311q-.065-.158-.115-.323t-.084-.333q-.033-.169-.05-.34T8 12.5v-.527M2.5 12H8m-5.5 3H8M3.5 3.5l17 17");
}

</style>
