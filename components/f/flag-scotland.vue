<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ft5dv1b6b"><circle class="x-17r5b1h"/><path class="a8vmz8iub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-scotland" /></template>
<style>
.a8vmz8iub {
  fill: var(--svg-color--eee, #EEE);
  d: path("M57.972 16.974L38.539 32l19.433 15.026a30 30 0 0 1-2.046 3.075l-.36.466a30 30 0 0 1-2.492 2.785L32 37.056L10.926 53.352a30 30 0 0 1-2.49-2.782l-.364-.471a30 30 0 0 1-2.044-3.073L25.461 32L6.028 16.974A30 30 0 0 1 8.074 13.9l.36-.466a30 30 0 0 1 2.492-2.784L32 26.944l21.074-16.296q1.332 1.316 2.494 2.787l.356.461a30 30 0 0 1 2.048 3.078");
}

.ft5dv1b6b {
  fill: none;
}

.x-17r5b1h {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--0065bd, #0065BD);
}

</style>
