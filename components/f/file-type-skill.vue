<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="rlchu4bbo"><path class="m7r1gybom"/><path class="llt6oibol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-skill" /></template>
<style>
.llt6oibol {
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--2-71px, 2.71px);
  d: path("m16 6.97l7.82 4.51v9.04L16 25.03l-7.82-4.51v-9.04z");
}

.m7r1gybom {
  d: path("m16 2l12.12 7v14L16 30L3.88 23V9z");
}

.rlchu4bbo {
  fill: var(--svg-color--dedede, #dedede);
}

</style>
