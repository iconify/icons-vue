<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ljbmbbclg"/><path class="sh4jj2bep"/><path class="cc5q7eb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-lua" /></template>
<style>
.cc5q7eb3k {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.29 11.56a3.14 3.14 0 1 0 6.28 0a3.14 3.14 0 1 0-6.28 0m-4.19 9.79v-.79H9.63v-6.23h-.9v7.02zm4.82 0V16.3h-.8v2.79c0 1.03-.54 1.7-1.38 1.7a.95.95 0 0 1-1.04-.99v-3.5h-.8v3.82c0 .83.63 1.37 1.6 1.37a1.9 1.9 0 0 0 1.7-.92v.78zm5.88-.02v-.6l-.18.01q-.43 0-.44-.4v-2.8q-.01-1.37-1.9-1.38c-1.22 0-1.97.47-2.02 1.64h.81c.07-.62.43-.9 1.19-.9q1.1.02 1.12.75v.21c0 .34-.2.48-.83.56a6 6 0 0 0-1.62.3a1.3 1.3 0 0 0-.9 1.32c0 .91.64 1.45 1.67 1.45a2.4 2.4 0 0 0 1.71-.74a.86.86 0 0 0 .83.67a2 2 0 0 0 .55-.1m-1.4-1.72a1.37 1.37 0 0 1-1.52 1.19c-.63 0-1-.22-1-.77c0-.53.36-.76 1.22-.89a4 4 0 0 0 1.3-.28z");
}

.ljbmbbclg {
  fill: none;
  stroke: var(--svg-color--gray, gray);
  stroke-dasharray: 1.209;
  stroke-width: var(--svg-stroke-width--0-33px, 0.33px);
  d: path("M28.33 9.7a13.85 13.85 0 1 1-3.81-4.62");
}

.sh4jj2bep {
  fill: var(--svg-color--navy, navy);
  d: path("M5.29 16a10.71 10.71 0 1 0 21.42 0a10.71 10.71 0 1 0-21.42 0M23.57 5.29a3.14 3.14 0 1 0 6.28 0a3.14 3.14 0 1 0-6.28 0");
}

</style>
