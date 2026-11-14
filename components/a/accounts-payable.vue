<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jswp9ul4z"/><path class="n2vcbgbba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accounts-payable" /></template>
<style>
.jswp9ul4z {
  d: path("M13.6 18.5H2.5v-13h19v7.2");
}

.n2vcbgbba {
  d: path("M14.928 12.653Q15 12.331 15 12q0-.147-.014-.294t-.044-.291q-.028-.145-.071-.286t-.099-.277t-.126-.266t-.152-.253q-.081-.122-.175-.236t-.198-.218q-.104-.105-.218-.198t-.236-.175t-.253-.152t-.266-.126t-.277-.099t-.286-.071t-.291-.044Q12.147 9 12 9t-.294.014q-.147.015-.291.044q-.145.028-.286.071t-.277.099t-.266.126t-.253.152q-.122.081-.236.175t-.218.198q-.105.104-.198.218t-.175.236t-.152.253t-.126.266t-.099.277t-.071.286t-.044.291Q9 11.853 9 12t.014.294q.015.147.044.291q.028.145.071.286t.099.277t.126.266t.152.253q.081.122.175.236t.198.218q.104.105.218.198t.236.175t.253.152t.266.126t.277.099t.286.071t.291.044Q11.853 15 12 15q.379 0 .746-.094q.368-.095.7-.277M15 21l5.25-5.25m-4-.25h4.25v4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
