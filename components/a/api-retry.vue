<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e2xym4b5u"/><path class="t7j_8-bdw"/><path class="r11s8kbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:api-retry" /></template>
<style>
.e2xym4b5u {
  d: path("m14.716 13.892l-4.433 2.217q-.182.091-.381.138q-.198.047-.402.047t-.402-.047t-.381-.138l-5.25-2.625q-.108-.054-.208-.123t-.19-.151q-.09-.081-.167-.175t-.141-.197t-.113-.214t-.082-.228t-.049-.237t-.017-.241V7.082q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l5.25-2.625q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l5.25 2.625q.109.054.208.123q.1.069.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v3.69");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r11s8kbqb {
  d: path("m19.5 11.75l-2 2l2 2");
}

.t7j_8-bdw {
  d: path("m2.5 6l7 3.5l7-3.5m-7 3.5v7m8-2.75a3.75 3.75 0 1 1-3.75 3.75");
}

</style>
