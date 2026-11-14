<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z7nok49yi"/><path class="rdiyroork"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:co-driver" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rdiyroork {
  d: path("M5 17.5c2-4 4.5 0 7-2m3.5-1c-2-2.5-3.5-4.5-3.5-7a3.5 3.5 0 0 1 7 0c0 2.5-1.5 4.5-3.5 7");
}

.z7nok49yi {
  d: path("M21.5 9.463v8.956q0 .117-.018.233q-.019.116-.055.228t-.089.216t-.121.2t-.152.179q-.082.083-.177.153t-.198.123q-.105.054-.216.091l-4.534 1.511q-.215.072-.441.077q-.227.005-.445-.057l-6.108-1.746q-.218-.062-.445-.057q-.226.005-.441.077l-3.586 1.195q-.084.028-.171.046t-.176.025q-.088.008-.177.005t-.176-.016q-.088-.014-.174-.037q-.085-.024-.168-.058q-.082-.033-.159-.076q-.078-.043-.15-.095t-.138-.112t-.123-.128q-.058-.067-.107-.141q-.05-.074-.09-.153q-.041-.079-.072-.162t-.051-.17q-.021-.086-.032-.174t-.01-.177V9.081q0-.117.018-.233q.019-.116.055-.228t.089-.216q.053-.105.121-.2q.069-.095.152-.179t.177-.153t.198-.123t.216-.091L8.06 6.147q.215-.072.441-.077q.227-.005.445.057l.418.119M8.5 6v13.5m7-2.2v4.2");
}

</style>
