<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i-v4vcbjz"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:infra-apply" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.i-v4vcbjz {
  d: path("M13.343 20.5H5q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T3.5 19V5q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119t.099-.109t.109-.099q.057-.046.119-.087t.126-.076t.133-.063t.139-.049t.142-.036q.073-.015.146-.022T5 3.5h14q.074 0 .147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146T20.5 5v7.279M3.5 12h17m-13-4.25h.01m-.01 8.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
