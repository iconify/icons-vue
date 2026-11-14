<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s44ets4kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-void" /></template>
<style>
.s44ets4kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.445 17.392q-.225-.241-.402-.52t-.298-.586t-.183-.631T2.5 15V9q0-.172.017-.343t.05-.34q.034-.168.084-.333t.115-.323q.066-.159.147-.311t.177-.294q.095-.143.204-.276q.11-.133.231-.255q.122-.121.255-.231q.133-.109.276-.204q.142-.096.294-.177t.311-.147q.158-.065.323-.115t.333-.084t.34-.05Q5.828 5.5 6 5.5h8m6.491 1.041q.24.244.429.529q.188.285.318.601t.196.652T21.5 9v6q0 .172-.017.343t-.05.34q-.034.168-.084.333t-.115.323q-.066.159-.147.311t-.177.294q-.095.143-.204.276q-.11.133-.231.255q-.122.121-.255.231q-.133.109-.276.204q-.142.096-.294.177t-.311.147t-.323.115t-.333.084q-.169.033-.34.05T18 18.5h-7.985M6 9.5h4m4 5h4m-13.5 6l15-17");
}

</style>
