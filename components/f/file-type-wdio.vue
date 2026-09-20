<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32,"left":-2,"top":-2};
const content = `<g class="bi12bsetm"><path class="rwb25z2bm"/><path class="xyh_occni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-wdio" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.rwb25z2bm {
  fill: var(--svg-color--ea5906, #ea5906);
  d: path("M2.188 0h23.626A2.19 2.19 0 0 1 28 2.188v23.626a2.19 2.19 0 0 1-2.188 2.188H2.187A2.19 2.19 0 0 1 0 25.813V2.187A2.19 2.19 0 0 1 2.188 0");
}

.xyh_occni {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M3.5 7v14h-.874V7h.876Zm15.313 0a7 7 0 1 1 0 14a7 7 0 0 1 0-14m-7 0L6.171 21h-.922L10.89 7zm7 .876a6.126 6.126 0 1 0 0 12.25a6.126 6.126 0 0 0 0-12.25");
}

</style>
