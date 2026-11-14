<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ptw7-qb-v"/><path class="fxi5swb1p"/><path class="n3-csvl0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biomass-plant" /></template>
<style>
.fxi5swb1p {
  d: path("M16.419 12.751q-.032-.145-.076-.286q-.044-.142-.099-.28q-.056-.137-.123-.269t-.145-.259q-.078-.126-.167-.245q-.088-.119-.187-.23q-.098-.111-.205-.213q-.107-.103-.223-.196q-.115-.093-.238-.176t-.253-.155t-.265-.133t-.275-.11t-.283-.087q-.144-.037-.29-.062t-.294-.037T13 10q-.172 0-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34T9.5 13.5q0 .167.016.334t.048.331t.079.325t.11.315q.062.156.139.304q.077.149.168.289q.09.141.194.272t.22.252t.242.23q.127.11.264.206q.137.097.282.18t.298.152q.152.069.31.123q.159.054.322.092q.162.039.328.062t.333.03");
}

.n3-csvl0e {
  d: path("M6 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm0 6h.01m6.99 0h.01m-3.51-6h.01m5.49 14c0-5 2-7 6.5-7c0 4.5-2 7-6.5 7Zm0 0l3.5-3.5");
}

.ptw7-qb-v {
  d: path("M2.5 13.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
