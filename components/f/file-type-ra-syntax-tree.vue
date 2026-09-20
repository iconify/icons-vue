<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path paint-order="stroke" class="m-qfj7ulk"/><path class="wehyry8jx"/><path class="vf-b_pb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ra-syntax-tree" /></template>
<style>
.m-qfj7ulk {
  stroke: var(--svg-color--fff, #fff);
  stroke-width: var(--svg-stroke-width--0-64px, 0.64px);
  d: path("M7.71 2.68a2.26 2.26 0 0 0-1.8.94c-.23.27-.38.64-.53.9L5 2.92H2.32v1.43h.98V8.7h-.98v1.47h4.56V8.71H5.45V6.64c.26-.76.68-1.55 1.43-1.92c.23-.16.46-.2.38.15v1.05h1.36L9 2.91a3.2 3.2 0 0 0-1.25-.23zm5.96 4.68a1.5 1.5 0 0 0-1.5 1.5a1.5 1.5 0 0 0 1.5 1.51a1.5 1.5 0 0 0 1.51-1.5a1.5 1.5 0 0 0-1.5-1.51z");
}

.vf-b_pb6p {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.08 23q0 .38.11.6q.11.2.38.27l-.45 1.44q-.65-.08-1.1-.3t-.68-.65q-.41.5-1.09.76q-.64.22-1.32.22q-1.13 0-1.81-.64q-.64-.64-.64-1.66q0-1.17.9-1.85q.95-.64 2.64-.64H24v-.26q0-.57-.37-.83q-.38-.26-1.06-.26l-.9.07l-1.14.3l-.49-1.43q.76-.3 1.51-.41q.76-.16 1.36-.16q1.62 0 2.38.68q.75.64.75 1.89zm-3.4.76q.38 0 .76-.19t.56-.6v-1.13h-.56q-.9 0-1.36.26q-.41.26-.41.8q0 .4.26.63q.26.27.72.27z");
}

.wehyry8jx {
  fill: var(--svg-color--30363b, #30363b);
  stroke: var(--svg-color--20262b, #20262b);
  stroke-width: var(--svg-stroke-width--0-53px, 0.53px);
  d: path("M16 13.05h13.74v16.33H16z");
}

</style>
