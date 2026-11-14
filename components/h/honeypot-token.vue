<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dk80bcckv"/><path class="n7tvkfbjs"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:honeypot-token" /></template>
<style>
.dk80bcckv {
  d: path("M6 2.5h12v3H6ZM11.981 21H7q-.147 0-.294-.014t-.291-.044q-.145-.028-.286-.071t-.277-.099q-.136-.057-.266-.126q-.13-.07-.253-.152q-.122-.081-.236-.175t-.218-.198t-.198-.218t-.175-.236q-.082-.123-.152-.253t-.126-.266t-.099-.277t-.071-.286q-.029-.144-.044-.291T4 18v-7c0-3 3-4 3-5.5h10C17 7 20 8 20 11v1.311");
}

.n7tvkfbjs {
  d: path("M4 11.5h4v2a1.5 1.5 0 0 0 3 0v-2h9M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
