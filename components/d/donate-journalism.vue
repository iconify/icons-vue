<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_yip3eqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:donate-journalism" /></template>
<style>
.s_yip3eqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 13.321V4.5q0-.074-.007-.147t-.022-.146t-.036-.142q-.021-.071-.049-.139t-.063-.133t-.076-.126t-.087-.119q-.047-.057-.099-.109t-.109-.099q-.057-.046-.119-.087t-.126-.076q-.065-.035-.133-.063t-.139-.049q-.07-.022-.142-.036q-.073-.015-.146-.022T15.5 3h-11q-.074 0-.147.007t-.146.022t-.142.036q-.071.021-.139.049t-.133.063t-.126.076t-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126t-.063.133t-.049.139t-.036.142t-.022.146T3 4.5v14q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036T5.5 21h8.809M21 13.518V8h-4M6.5 7.5h7m-7 4h7m-7 4h4m8 6l-2.75-3a2 2 0 0 1 2.75-2.25a2 2 0 0 1 2.75 2.25Z");
}

</style>
