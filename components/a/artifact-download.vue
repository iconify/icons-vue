<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wrc0koo8o"/><path class="a6_89kyto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:artifact-download" /></template>
<style>
.a6_89kyto {
  d: path("m3 6l7 3.5L17 6m-7 3.5V16M6.5 4.25l7 3.5M18 14.5V21m-2.75-2.75L18 21l2.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrc0koo8o {
  d: path("m15.484 13.258l-4.701 2.351q-.182.091-.381.138q-.198.047-.402.047t-.402-.047t-.381-.138l-5.25-2.625q-.108-.054-.208-.123t-.19-.151q-.09-.081-.167-.175t-.141-.197t-.113-.214t-.082-.228t-.049-.237T3 11.418V7.082q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l5.25-2.625q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l5.25 2.625q.109.054.208.123q.1.069.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v4.336q0 .236-.062.463");
}

</style>
