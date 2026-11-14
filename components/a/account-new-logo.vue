<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="clmusjblh"/><path class="zxo9xcbhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-new-logo" /></template>
<style>
.clmusjblh {
  d: path("M13.753 19.291q-.048.122-.105.239t-.123.23t-.139.221q-.074.107-.156.209t-.171.197q-.089.096-.185.184q-.095.089-.198.17q-.102.081-.21.155q-.108.073-.221.138t-.231.122t-.239.104t-.247.085q-.124.039-.252.068q-.127.029-.256.048q-.129.02-.259.029t-.261.01h-4q-.172 0-.343-.017t-.34-.05t-.333-.084t-.323-.115q-.159-.066-.311-.147t-.294-.177q-.143-.095-.276-.204q-.133-.11-.255-.231q-.121-.122-.231-.255q-.109-.133-.204-.276q-.096-.142-.177-.294t-.147-.311t-.115-.323t-.084-.333q-.033-.169-.05-.34T3 18V6q0-.172.017-.343t.05-.34t.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05T6.5 2.5h4q.172 0 .343.017t.34.05q.168.034.333.084t.323.115q.159.066.311.147t.294.177t.276.204q.133.11.255.231q.121.122.231.255q.109.133.204.276q.096.142.177.294t.147.311q.065.158.115.323t.084.333t.05.34T14 6v10.342M6.75 6.5h.01m3.49 0h.01M6.75 10h.01m3.49 0h.01m-3.51 3.5h.01m3.49 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxo9xcbhe {
  d: path("M7 21.5v-4h3v4m9-6.75q.25 3 2.75 3.25q-2.5.25-2.75 3.25q-.25-3-2.75-3.25q2.5-.25 2.75-3.25");
}

</style>
