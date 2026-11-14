<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1pn4acuy"/><path class="u_7momcho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contract-test" /></template>
<style>
.b1pn4acuy {
  d: path("M4 6za1.5 1.5 0 0 1 1.5 1.5v5A1.5 1.5 0 0 1 4 14a1.5 1.5 0 0 1-1.5-1.5v-5A1.5 1.5 0 0 1 4 6m15.12 7.715q-.144-.105-.26-.24q-.115-.135-.196-.293t-.122-.331q-.042-.173-.042-.351v-5q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076q.065-.035.133-.063t.139-.049q.07-.022.142-.036q.073-.015.146-.022T20 6t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142q.015.073.022.146t.007.147v5q0 .256-.085.498");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u_7momcho {
  d: path("M18.5 7.5H15l-3.5-2l-4 3.5a1.25 1.25 0 0 0 1.75 1.75L12 8.5m-6.5 4l4 2.5H12l6.5-3m-3.75 6l2 2L21 15.75");
}

</style>
