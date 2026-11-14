<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-tcr69lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:entertainment-news" /></template>
<style>
.g-tcr69lo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 9.221V4.5q0-.074-.007-.147t-.022-.146t-.036-.142q-.021-.071-.049-.139t-.063-.133t-.076-.126t-.087-.119q-.047-.057-.099-.109t-.109-.099q-.057-.046-.119-.087t-.126-.076q-.065-.035-.133-.063t-.139-.049q-.07-.022-.142-.036q-.073-.015-.146-.022T15.5 3h-11q-.074 0-.147.007t-.146.022t-.142.036q-.071.021-.139.049t-.133.063t-.126.076t-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126t-.063.133t-.049.139t-.036.142t-.022.146T3 4.5v14q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126q.108.058.221.105q.114.047.231.082t.238.06t.243.036T5.5 21h7.209M21 13.618V8h-3.082m-.3 0H17M6.5 7.5h7m-7 4h7m-7 4h3m8.25-1.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
