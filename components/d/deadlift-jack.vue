<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugk8ziulv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deadlift-jack" /></template>
<style>
.ugk8ziulv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5zA1.5 1.5 0 0 1 7 4v7a1.5 1.5 0 0 1-1.5 1.5A1.5 1.5 0 0 1 4 11V4a1.5 1.5 0 0 1 1.5-1.5m12.12 9.715q-.144-.105-.26-.24q-.115-.135-.196-.293t-.122-.331Q17 11.178 17 11V4q0-.074.007-.147t.022-.146t.036-.142q.021-.071.049-.139t.063-.133t.076-.126t.087-.119q.047-.057.099-.109t.109-.099q.057-.046.119-.087t.126-.076q.065-.035.133-.063t.139-.049q.07-.022.142-.036q.073-.015.146-.022T18.5 2.5t.147.007t.146.022q.072.014.142.036q.071.021.139.049t.133.063t.126.076q.062.041.119.087q.057.047.109.099t.099.109t.087.119t.076.126t.063.133t.049.139t.036.142t.022.146T20 4v7q0 .111-.016.221q-.017.11-.049.217q-.033.106-.081.207q-.047.1-.11.192q-.062.093-.137.175t-.161.152t-.182.127t-.199.099M7 7.5h10M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
