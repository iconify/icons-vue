<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lf8kt_akq"/><path class="gtshf8bwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charity-sleepout" /></template>
<style>
.gtshf8bwo {
  d: path("m8.5 18.5l1.5-4l1.5 4m7.25-2.75a3 3 0 1 0 3 3a2.75 2.75 0 0 1-3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf8kt_akq {
  d: path("M12.936 18.5H5.332q-.056 0-.111-.003q-.056-.004-.111-.011T5 18.468q-.055-.01-.108-.024q-.054-.014-.107-.031t-.105-.039q-.051-.02-.102-.044t-.099-.051t-.095-.057t-.092-.064q-.044-.033-.087-.068t-.083-.075q-.04-.038-.078-.079t-.073-.084q-.035-.044-.067-.089t-.061-.093q-.03-.047-.056-.096t-.049-.1t-.043-.103t-.036-.105q-.017-.053-.03-.107t-.022-.109t-.016-.11q-.006-.056-.008-.111q-.003-.056-.002-.112q.001-.055.006-.111q.005-.055.013-.11t.019-.11t.027-.108t.033-.106q.019-.053.04-.104t.047-.101L8.435 6.63q.054-.108.123-.208t.15-.19t.176-.167q.093-.077.196-.141t.214-.112q.111-.049.228-.082t.237-.05t.241-.017t.241.017t.237.05t.228.082t.214.112t.196.141t.176.167q.081.09.15.19t.123.208l3.749 7.496");
}

</style>
