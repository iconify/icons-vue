<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ju8lcp75s"/><path class="r58_zncxm"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:benefits-payment-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ju8lcp75s {
  d: path("M11.9 18H2.5V5h19v8.1");
}

.r58_zncxm {
  d: path("M14.588 13.017q.203-.345.307-.731Q15 11.9 15 11.5q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277t-.126-.266t-.152-.253q-.081-.122-.175-.236t-.198-.218q-.104-.105-.218-.198t-.236-.175t-.253-.152t-.266-.126t-.277-.099t-.286-.071t-.291-.044Q12.147 8.5 12 8.5t-.294.014q-.147.015-.291.044q-.145.028-.286.071t-.277.099t-.266.126t-.253.152q-.122.081-.236.175t-.218.198q-.105.104-.198.218t-.175.236t-.152.253t-.126.266t-.099.277t-.071.286t-.044.291Q9 11.353 9 11.5t.014.294q.015.147.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044q.147.014.294.014q.352 0 .695-.082q.343-.081.657-.24M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
