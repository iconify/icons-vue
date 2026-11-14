<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpczykfqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jet-fuel" /></template>
<style>
.rpczykfqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.655 12H6c-1.5 0-2.5-1-2.75-2.5l-.75-7h2L8 7h10.5q.123 0 .245.012t.243.036t.238.06t.231.082q.113.047.221.105q.109.058.211.126q.102.069.197.146q.095.078.182.165t.165.182t.146.197t.126.211t.105.221q.047.114.082.231t.06.238t.036.243T21 9.5q0 .194-.03.385t-.088.375q-.059.185-.146.358q-.086.173-.198.331q-.113.157-.248.296t-.289.255q-.155.116-.326.207t-.354.154M12.5 12l-3 4.5H7m11-1.75c-1 1.25-2.75 3-2.75 4.25a2.75 2.75 0 0 0 5.5 0c0-1.25-1.75-3-2.75-4.25Z");
}

</style>
