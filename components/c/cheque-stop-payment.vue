<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ypz0bfbsl"/><path class="xw6uabiaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-stop-payment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xw6uabiaz {
  d: path("m19.779 15.206l1.015 1.015a1.5 1.5 0 0 1 .44 1.061v1.436a1.5 1.5 0 0 1-.44 1.061l-1.015 1.015a1.5 1.5 0 0 1-1.061.44h-1.436a1.5 1.5 0 0 1-1.061-.44l-1.015-1.015a1.5 1.5 0 0 1-.44-1.061v-1.436a1.5 1.5 0 0 1 .44-1.061l1.015-1.015a1.5 1.5 0 0 1 1.061-.44h1.436a1.5 1.5 0 0 1 1.061.44M16.75 18h2.5");
}

.ypz0bfbsl {
  d: path("M12.015 18.5H6q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T2.5 15V9q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 5.5 6 5.5h12q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T21.5 9v4.042M6 9.5h5.5m-5.5 5h3.5");
}

</style>
