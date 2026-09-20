<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGM9iSmjkR"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="w_5sf-1ox"/><path class="qi2zqhpdh"/></g></mask></defs><circle mask="url(#SVGM9iSmjkR)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:comet-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.qi2zqhpdh {
  d: path("M13.907 19.949a5.921 5.921 0 1 1-7.677-9.015l7.08-5.836c1.078-.89 2.68.05 2.43 1.425l-.263 1.445l4.558-3.799c1.304-1.086 3.125.487 2.24 1.934l-2.858 4.678l.896-.1c1.458-.162 2.258 1.649 1.156 2.618zm-6.89-1.897a3.92 3.92 0 0 0 5.57.395l6.37-5.603l-.333.037c-1.24.138-2.096-1.209-1.445-2.273l1.812-2.965l-3.292 2.743c-1.077.898-2.687-.041-2.436-1.42l.264-1.456l-6.024 4.967a3.92 3.92 0 0 0-.485 5.575");
}

.w_5sf-1ox {
  d: path("M9.29 16.093a1 1 0 1 0 1.52-1.3a1 1 0 0 0-1.52 1.3m2.71 1.63a3 3 0 1 1-3.9-4.56a3 3 0 0 1 3.9 4.56");
}

</style>
