<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrimolbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coast-guard-officer" /></template>
<style>
.vrimolbsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6c2-3.5 12-3.5 14 0l-3 2.5H8Zm3.5 5.25q0 .172.017.343t.05.34q.034.168.084.333t.115.323q.066.159.147.311t.177.294t.204.276q.11.133.231.255q.122.121.255.231q.133.109.276.204q.142.096.294.177t.311.147q.158.065.323.115t.333.084q.169.033.34.05t.343.017q.357 0 .708-.072m2.158-1.419q.154-.219.272-.459t.2-.496q.08-.256.121-.521t.041-.533M4.5 21.5c0-2.5 3.25-4 7.5-4q.326 0 .642.012M18.5 15l3 1v2.5c0 1.75-1.25 2.75-3 3.5c-1.75-.75-3-1.75-3-3.5V16Z");
}

</style>
