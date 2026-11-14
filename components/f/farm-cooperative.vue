<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xtbf4lb9c"/><path class="dm_f7_b5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farm-cooperative" /></template>
<style>
.dm_f7_b5b {
  d: path("M10.75 7.5h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5V9a1.5 1.5 0 0 1 1.5-1.5m2.5 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M13 21.5a1.75 1.75 0 0 1 3.5 0m1.5 0a1.75 1.75 0 0 1 3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtbf4lb9c {
  d: path("M10.297 20.5H4q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T2.5 19v-8.578q0-.207.056-.406t.164-.376l2.306-3.773q.11-.18.265-.322t.344-.237l4.944-2.473q.156-.078.326-.118t.345-.04t.345.04t.326.118l4.944 2.473q.189.094.344.237q.155.142.265.322L19.78 9.64q.108.177.164.376t.056.406v1.502");
}

</style>
