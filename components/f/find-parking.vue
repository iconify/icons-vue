<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ka8105yyx"/><path class="vvlbaq4dh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:find-parking" /></template>
<style>
.ka8105yyx {
  d: path("M15.197 13H2.5V9.5l3-1l2-4.5H13l2.5 4.5l3 1v3.003");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vvlbaq4dh {
  d: path("M4.5 14.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm9.807-1.163q-.123-.139-.272-.248q-.149-.11-.318-.186q-.169-.075-.351-.114T13 13q-.086 0-.172.008t-.169.026q-.085.016-.167.041t-.162.058q-.079.033-.155.074t-.147.088q-.072.048-.138.102q-.067.055-.127.116q-.061.06-.116.127q-.054.066-.102.138q-.048.071-.088.147q-.041.076-.074.155q-.033.08-.058.162t-.041.167t-.026.169t-.008.172q0 .141.023.28q.022.139.067.273q.044.133.109.258q.066.125.15.238q.085.113.186.21q.101.098.217.179t.243.141t.262.1M15.25 17.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
