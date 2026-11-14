<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5tfdg7sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boundary-off" /></template>
<style>
.l5tfdg7sf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.967 6h5.366q.129 0 .256.019q.128.019.251.056q.124.037.24.092q.117.055.224.127q.107.071.203.158q.096.086.178.186q.081.099.148.21t.116.229l3.541 8.5q.105.252.128.524t-.037.538M14.094 18H5.125q-.054 0-.107-.003q-.054-.004-.107-.01q-.054-.007-.107-.017q-.052-.01-.105-.023q-.052-.013-.103-.029t-.101-.036q-.05-.019-.099-.041t-.097-.048t-.093-.054t-.089-.059t-.086-.065t-.082-.069q-.04-.037-.077-.075q-.038-.039-.073-.079q-.035-.041-.067-.084q-.033-.043-.063-.087q-.03-.045-.057-.092q-.027-.046-.051-.094t-.045-.098t-.039-.1t-.033-.102t-.027-.104l-.02-.106q-.008-.053-.013-.106q-.006-.054-.008-.107v-.108q.001-.054.006-.107q.005-.054.013-.107t.019-.106t.026-.104t.032-.103q.017-.05.038-.1l2.395-5.75M3.5 3.5l17 17");
}

</style>
