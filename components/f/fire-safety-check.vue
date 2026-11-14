<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ze7ofkjxr"/><path class="xxia9rbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-safety-check" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxia9rbmd {
  d: path("M7.75 5.5h3.5V8h-3.5Zm1.75 0v-2m-3 0H13m-1.75 3.25h4.25c1.75 0 2.5 1.25 2.5 3V13m-3.25 5l2 2L21 15.75");
}

.ze7ofkjxr {
  d: path("M13.482 20.691q-.017.085-.048.166t-.075.155t-.1.139q-.057.066-.123.121q-.067.055-.142.097t-.156.072t-.167.044t-.171.015h-6q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T5.5 20.5V9q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057T6.5 8h6q.098 0 .195.019t.188.057t.173.093t.151.124t.124.151t.093.173t.057.188T13.5 9v6.286");
}

</style>
