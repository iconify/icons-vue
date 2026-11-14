<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="i66wpfbhy"/><path class="k4x6rpb9s"/><path class="qck5q7bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ats" /></template>
<style>
.i66wpfbhy {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--ffff40, #ffff40);
  fill-opacity: var(--svg-fill-opacity--0-88, 0.88);
}

.k4x6rpb9s {
  fill: none;
  stroke: var(--svg-color--red, red);
  stroke-width: var(--svg-stroke-width--2-21px, 2.21px);
  d: path("m4.38 12.36l2.76-1.95a2.99 4.4 0 0 1 4.28 3.97v5.04a3.59 3.59 0 0 0 3.59 3.59h12.25m-15.82-9.57l-6.99 9.64");
}

.qck5q7bdz {
  fill: var(--svg-color--00f, #00f);
  d: path("M14.6 9.34h11.2v2.8h-4.7v1.14h5.6v7.62h-13v-7.62h5.6v-1.14h-4.7zm.9 6.74v2.02h3.8v-2.02zm5.6 0v2.02h3.8v-2.02z");
}

</style>
