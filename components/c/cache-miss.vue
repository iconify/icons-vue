<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="regthr-ds"/><path class="k51mqjbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cache-miss" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k51mqjbge {
  d: path("m2.5 6.5l8 4l8-4m-8 4v9m-4-15l8 4m0 6L21 21m0-6.5L14.5 21");
}

.regthr-ds {
  d: path("m13.691 17.905l-2.408 1.204q-.182.091-.381.138q-.198.047-.402.047t-.402-.047t-.381-.138l-6.25-3.125q-.108-.054-.208-.123t-.19-.151q-.09-.081-.167-.175t-.141-.197t-.113-.214t-.082-.228t-.049-.237t-.017-.241V7.582q0-.121.017-.241q.016-.121.049-.237q.033-.117.082-.228t.113-.214t.141-.197t.167-.175t.19-.151t.208-.123l6.25-3.125q.182-.091.381-.138q.198-.047.402-.047t.402.047t.381.138l6.25 3.125q.109.054.208.123q.1.069.19.151t.167.175t.141.197q.064.103.113.214t.082.228t.049.237q.017.12.017.241v5.472");
}

</style>
