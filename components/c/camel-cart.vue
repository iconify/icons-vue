<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r61adac2w"/><rect class="fzy6l0xvw"/><circle class="e3ijufb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camel-cart" /></template>
<style>
.e3ijufb_j {
  cx: 5.5px;
  cy: 19.25px;
  r: 1.75px;
}

.fzy6l0xvw {
  width: 5.5px;
  height: 3px;
  x: 2.75px;
  y: 11.5px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r61adac2w {
  d: path("m11.89 11.42l.57-.71q.64-.77 1.35-.98q.72-.2 1.54.31t1.44 1.12q.61.62 1.03-.29l.19-.43q.42-.91.83-1.32q.4-.41 1.22-.31t.92.51q.11.41-.5.72q-.62.31-.93 1.23t-.91 1.72l-.02.04q-.6.8-1.6.8h-3.95q-1 0-1.41-.82t.23-1.59m1 2.41V20m4.72-6.17V20m-9.36-7h3.25");
}

</style>
