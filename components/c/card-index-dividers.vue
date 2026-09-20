<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tz3x1qbcd"/><path class="jfng8fb-l"/><path class="pq6muvb6m"/><path class="wmre3hbil"/><path class="kb7y3sbpx"/><path class="sg4lzub7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:card-index-dividers" /></template>
<style>
.jfng8fb-l {
  fill: var(--svg-color--ccb656, #ccb656);
  d: path("M121.1 102.3H19.9c-2.1 0-3.9-1.7-3.9-3.9V31.7c0-2.1 1.7-3.9 3.9-3.9H125v70.7c0 2.1-1.7 3.8-3.9 3.8");
}

.kb7y3sbpx {
  fill: var(--svg-color--f79329, #f79329);
  d: path("M42.8 34.3H7.2c-2.3 0-4.2 1.9-4.2 4.2v13.2h44V38.5c0-2.3-1.9-4.2-4.2-4.2");
}

.pq6muvb6m {
  fill: var(--svg-color--1a6ca2, #1a6ca2);
  d: path("M83.2 25.3H47.7c-2.4 0-4.3 1.9-4.3 4.3V43h44V29.6c.1-2.4-1.9-4.3-4.2-4.3");
}

.sg4lzub7l {
  fill: var(--svg-color--f7e599, #f7e599);
  d: path("M108.1 120H6.9c-2.1 0-3.9-1.7-3.9-3.9V45.5h105.1c2.1 0 3.9 1.7 3.9 3.9v66.8c0 2.1-1.7 3.8-3.9 3.8");
}

.tz3x1qbcd {
  fill: var(--svg-color--a13300, #a13300);
  d: path("M120.7 17.6H85.3c-2.4 0-4.3 1.9-4.3 4.3v13.4h44V21.9c0-2.4-1.9-4.3-4.3-4.3");
}

.wmre3hbil {
  fill: var(--svg-color--e5d07a, #e5d07a);
  d: path("M115.1 111H13.9c-2.1 0-3.9-1.7-3.9-3.9V40.3c0-2.1 1.7-3.9 3.9-3.9h101.2c2.1 0 3.9 1.7 3.9 3.9v66.8c0 2.1-1.7 3.9-3.9 3.9");
}

</style>
