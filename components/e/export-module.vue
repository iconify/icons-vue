<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b98nvfzzp"/><path class="omit5ccxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:export-module" /></template>
<style>
.b98nvfzzp {
  d: path("m15.971 9.485l.062.031q.109.054.208.123q.1.069.19.151t.167.175t.141.197t.113.214t.082.228q.033.116.049.237q.017.12.017.241v5.836q0 .121-.017.241q-.016.121-.049.237q-.033.117-.082.228t-.113.214t-.141.197t-.167.175t-.19.151q-.099.069-.208.123l-5.25 2.625q-.182.091-.381.138q-.198.047-.402.047t-.402-.047t-.381-.138l-5.25-2.625q-.108-.054-.208-.123t-.19-.151t-.167-.175t-.141-.197t-.113-.214t-.082-.228q-.033-.116-.049-.237Q3 17.039 3 16.918v-5.836q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l5.25-2.625q.166-.083.345-.129q.18-.047.365-.054q.185-.008.368.023t.355.1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.omit5ccxp {
  d: path("m3 10l7 3.5l2.66-1.33m1.163-.581L17 10m-7 3.5v8m2-12L19.5 2M15 2h4.5v4.5");
}

</style>
