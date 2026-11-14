<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ffv4tubuq"/><path class="tg-_q3bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-gas-cylinder" /></template>
<style>
.ffv4tubuq {
  d: path("M12.584 21.5H3V10q0-.147.014-.294t.044-.291q.028-.145.071-.286t.099-.277t.126-.266t.152-.253t.175-.236t.198-.218t.218-.198t.236-.175t.253-.152q.13-.069.266-.126t.277-.099q.141-.043.286-.071q.144-.029.291-.044T6 7h4.5q.147 0 .294.014t.291.044q.145.028.286.071t.277.099q.136.057.266.126q.13.07.253.152q.122.081.236.175t.218.198q.105.104.198.218t.175.236t.152.253t.126.266t.099.277t.071.286t.044.291q.014.147.014.294v3.516");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tg-_q3bfn {
  d: path("M6.75 7V5h3v2m-1.5-2V2.5m-2 0h4m7.811 12.561l1.878 1.878a1.5 1.5 0 0 1 0 2.122l-1.878 1.878a1.5 1.5 0 0 1-2.122 0l-1.878-1.878a1.5 1.5 0 0 1 0-2.122l1.878-1.878a1.5 1.5 0 0 1 2.122 0");
}

</style>
