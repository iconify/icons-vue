<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="haq85sbhp"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:document-stamp-pending" /></template>
<style>
.haq85sbhp {
  d: path("M8.5 11.5V9.75C8.5 8.75 7.25 8 7.25 6a3.25 3.25 0 0 1 6.5 0c0 2-1.25 2.75-1.25 3.75v1.75m.514 4.5H5.25q-.111 0-.221-.011t-.218-.032t-.214-.054t-.208-.074q-.102-.043-.2-.095q-.097-.052-.189-.113t-.177-.132t-.164-.148t-.148-.164q-.07-.085-.132-.177q-.061-.092-.113-.189q-.052-.098-.095-.2q-.042-.102-.074-.208t-.054-.214t-.032-.218T3 13.75t.011-.221t.032-.218q.022-.108.054-.214t.074-.208q.043-.102.095-.2q.052-.097.113-.189t.132-.177q.07-.086.148-.164t.164-.148t.177-.132q.092-.061.189-.113q.098-.052.2-.095q.102-.042.208-.074t.214-.054t.218-.032t.221-.011h10.5q.36 0 .702.112t.631.325M4.5 19.5H13m2.5-4.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

</style>
