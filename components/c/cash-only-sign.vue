<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qfwjqwbje"/><path class="joxy9s7cg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-only-sign" /></template>
<style>
.joxy9s7cg {
  d: path("M11.474 12.697q.257-.375.391-.809Q12 11.454 12 11q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277t-.126-.266t-.152-.253q-.081-.122-.175-.236t-.198-.218q-.104-.105-.218-.198t-.236-.175t-.253-.152t-.266-.126t-.277-.099t-.286-.071t-.291-.044Q9.147 8 9 8t-.294.014q-.147.015-.291.044q-.145.028-.286.071t-.277.099t-.266.126t-.253.152q-.122.081-.236.175t-.218.198t-.198.218t-.175.236t-.152.253q-.069.13-.126.266t-.099.277q-.043.141-.071.286q-.029.144-.044.291T6 11t.014.294q.015.147.044.291q.028.145.071.286t.099.277q.057.136.126.266q.07.13.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175q.123.082.253.152t.266.126t.277.099t.286.071t.291.044T9 14q.311 0 .615-.064q.304-.063.589-.188q.284-.125.537-.305t.464-.409M17.5 8.5h.01m-3.51 7h8v5.75h-8Zm0 2h8m-8-3.25L22 22");
}

.qfwjqwbje {
  d: path("M11.2 19H2.5V5h19v7.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
