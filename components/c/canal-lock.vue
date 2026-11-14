<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyu81snag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:canal-lock" /></template>
<style>
.iyu81snag {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 2.25h-.5q-.932 0-1.591.659T2.25 4.5v14q0 2.25 2.25 2.25H5q.599 0 1.038-.159q.099.077.218.118q.118.041.244.041h11q.126 0 .244-.041q.119-.041.218-.118q.439.159 1.038.159h.5q2.25 0 2.25-2.25v-14q0-2.25-2.25-2.25H19q-2.25 0-2.25 2.25v6.037q-2.195 1.002-4.391-.195q-2.554-1.394-5.109-.497V4.5q0-2.25-2.25-2.25m2.25 9.213q2.195-1.002 4.391.195q2.554 1.394 5.109.497V18.5q0 .413.076.75H7.174q.076-.337.076-.75z");
}

</style>
