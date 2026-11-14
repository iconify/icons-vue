<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h-nqrsq4q"/><path class="oztzrc8hw"/><path class="tzyxxwbzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backlog-cancel" /></template>
<style>
.h-nqrsq4q {
  d: path("M12.9 9h.1q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311t.115.323t.084.333q.033.169.05.34t.017.343v.042m-.997 6.905q-.245.25-.534.447q-.289.196-.611.332q-.323.136-.666.205q-.342.069-.692.069H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 17v-4.5q0-.144.012-.287t.035-.285t.059-.281t.081-.276t.104-.268q.057-.131.125-.258t.146-.247t.166-.235t.185-.22t.202-.204t.218-.187t.232-.169q.12-.079.246-.149t.257-.128t.267-.106q.135-.048.274-.085");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oztzrc8hw {
  d: path("M10.15 6.25h7.1q.098 0 .196.01q.098.009.194.028q.097.02.191.048q.094.029.184.066q.091.038.178.084q.086.046.168.101t.158.117t.145.132q.07.069.132.145t.117.158t.101.168q.046.087.084.178q.037.09.066.184q.028.094.048.191q.019.096.028.194t.01.196v7.072");
}

.tzyxxwbzx {
  d: path("M8 3.5h12a2 2 0 0 1 2 2V15M3.5 3.5l17 17");
}

</style>
