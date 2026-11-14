<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="detzozx1m"/><path class="fjisffbti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-request-join" /></template>
<style>
.detzozx1m {
  d: path("M2.89 13.606q-.192-.372-.291-.78Q2.5 12.419 2.5 12V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6 2.5h12q.172 0 .343.017t.34.05q.168.034.333.084t.323.115t.311.147t.294.177q.143.095.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333q.033.169.05.34T21.5 6v6q0 .172-.017.343t-.05.34q-.034.168-.084.333t-.115.323q-.066.159-.147.311t-.177.294t-.204.276q-.11.133-.231.255q-.122.121-.255.231q-.133.109-.276.204q-.142.096-.294.177t-.311.147q-.158.065-.323.115t-.333.084q-.169.033-.34.05T18 15.5h-.685");
}

.fjisffbti {
  d: path("M5.5 14.5v3a4 4 0 0 0 4 4H11a3.5 3.5 0 0 0 3.5-3.5v-5m-6 3.5V11m3 5.5v-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
