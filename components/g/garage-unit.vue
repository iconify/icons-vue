<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="emycbkbcr"/><path class="jxa8v5bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garage-unit" /></template>
<style>
.emycbkbcr {
  d: path("m2.5 9.5l9.5-6l9.5 6M3.5 9v12.5M20.5 9v3.6m-7.634 8.625q-.19.134-.412.205T12 21.5H7q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T5.5 20v-7.5q0-.074.007-.147t.022-.146q.014-.072.036-.142q.021-.071.049-.139t.063-.133t.076-.126q.041-.062.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T7 11h5q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109q.046.057.087.119t.076.126t.063.133t.049.139q.022.07.036.142q.015.073.022.146t.007.147v1.879M5.5 14h8m-8 3h7M8 19.5h3m6.438-4.25h1.875a2.19 2.19 0 0 1 2.187 2.188v1.875a2.19 2.19 0 0 1-2.187 2.187h-1.875a2.19 2.19 0 0 1-2.188-2.187v-1.875a2.19 2.19 0 0 1 2.188-2.188");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jxa8v5bhe {
  d: path("m17.5 17.5l1-.75v2.75");
}

</style>
