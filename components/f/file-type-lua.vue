<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b0y1c1bfn"/><path class="ybp0ixbjb"/><path class="tll0xjy8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-lua" /></template>
<style>
.b0y1c1bfn {
  fill: none;
  stroke: var(--svg-color--gray, gray);
  stroke-dasharray: 1.18;
  stroke-width: var(--svg-stroke-width--0-32px, 0.32px);
  d: path("M28.03 9.9a13.48 13.48 0 1 1-3.7-4.5");
}

.tll0xjy8h {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.29 11.7a3.06 3.06 0 1 0 6.1 0a3.06 3.06 0 1 0-6.1 0m-4.08 9.54v-.77H9.83V14.4h-.88v6.84zm4.69 0v-4.92h-.78v2.72c0 1-.53 1.65-1.34 1.65a.93.93 0 0 1-1.02-.96v-3.4H14v3.7c0 .82.6 1.34 1.55 1.34a1.9 1.9 0 0 0 1.66-.9v.77zm5.72-.02v-.59l-.17.01q-.42 0-.43-.39v-2.72q-.01-1.33-1.85-1.34c-1.19 0-1.92.45-1.97 1.6h.8c.06-.61.4-.88 1.15-.88q1.07.02 1.09.73v.2c0 .33-.2.47-.8.55a6 6 0 0 0-1.59.29a1.26 1.26 0 0 0-.87 1.28c0 .89.62 1.41 1.62 1.41a2.3 2.3 0 0 0 1.67-.72a.84.84 0 0 0 .8.66a2 2 0 0 0 .54-.1m-1.36-1.68a1.33 1.33 0 0 1-1.48 1.16c-.61 0-.97-.21-.97-.75c0-.51.35-.74 1.18-.86a4 4 0 0 0 1.27-.28z");
}

.ybp0ixbjb {
  fill: var(--svg-color--navy, navy);
  d: path("M5.6 16.03a10.42 10.42 0 1 0 20.85 0a10.42 10.42 0 1 0-20.84 0M23.4 5.61a3.06 3.06 0 1 0 6.1 0a3.06 3.06 0 1 0-6.1 0");
}

</style>
