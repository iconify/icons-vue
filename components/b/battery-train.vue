<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ng7cehe0u"/><path class="u_jypkz-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-train" /></template>
<style>
.ng7cehe0u {
  d: path("M12.928 16.5H4q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T3 15.5v-12q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T4 2.5h9q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T14 3.5v11.386");
}

.u_jypkz-r {
  d: path("M6 5.5h5V9H6Zm.5 6.5h.01m3.99 0h.01M6.5 16.5L5 20m5.5-3.5L12 20m4.5-3h3a1 1 0 0 1 1 1v.5h1V20h-1v.5a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1V18a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
