<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qsr4ysb1k"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bed-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qsr4ysb1k {
  d: path("M3.5 4v16m8.943-4.5H5q-.074 0-.147-.007t-.146-.022q-.072-.014-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087t-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126t-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T3.5 14v-1q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T5 11.5h14q.113 0 .224.017q.112.017.219.05q.108.033.21.082q.101.05.194.113q.093.064.176.141t.152.165t.127.186q.056.098.096.203M8.5 7.5h1a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-1a2 2 0 0 1-2-2a2 2 0 0 1 2-2M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
