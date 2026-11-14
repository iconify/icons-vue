<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="di2s28qxc"/><path class="zb7t69soe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:customer-not-home" /></template>
<style>
.di2s28qxc {
  d: path("M17.016 21H4V11l1.475-1.198m4.346-3.531L12 4.5l8 6.5v5.084");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zb7t69soe {
  d: path("M14.5 18.579v.921q0 .074-.007.147t-.022.146q-.014.072-.036.142q-.021.071-.049.139t-.063.133t-.076.126q-.041.062-.087.119q-.047.057-.099.109t-.109.099t-.119.087t-.126.076t-.133.063t-.139.049t-.142.036q-.073.015-.146.022T13 21h-2q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076q-.062-.041-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T9.5 19.5v-4q0-.174.04-.343q.039-.169.117-.324q.077-.156.188-.29q.11-.133.249-.238M4 4.5L20 20");
}

</style>
