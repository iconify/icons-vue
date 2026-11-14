<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a6uw6lb9g"/><path class="ydes0-r_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dev-dependency" /></template>
<style>
.a6uw6lb9g {
  d: path("m14.119 16.303l-3.295 1.758q-.19.102-.399.154t-.425.052t-.425-.052t-.399-.154l-5.75-3.067q-.104-.056-.2-.125t-.182-.151t-.16-.174t-.135-.194t-.107-.21t-.079-.223q-.031-.114-.047-.231T2.5 13.45v-5.9q0-.118.016-.236t.047-.231t.079-.223q.046-.109.107-.21q.061-.102.135-.194t.16-.174t.182-.151t.2-.125l5.75-3.067q.19-.102.399-.154T10 2.733t.425.052t.399.154l5.75 3.067q.104.056.2.125t.182.151t.16.174t.135.194t.107.21q.047.109.079.223q.031.114.047.231t.016.236v4.183");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydes0-r_v {
  d: path("m2.5 6.5l7.5 4l7.5-4m-7.5 4v8M21.75 16a2.5 2.5 0 1 1-2-1.75M17.5 18.5l-3 3");
}

</style>
