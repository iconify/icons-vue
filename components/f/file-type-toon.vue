<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="m_6i3tbwd"><path class="pbgzjtzrn"/><path class="kouv-mz8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-toon" /></template>
<style>
.kouv-mz8z {
  fill: none;
  d: path("M8 14V4H2h12m14 18v8m-8 0V20h6");
}

.m_6i3tbwd {
  stroke: var(--svg-color--dedede, #dedede);
  stroke-width: var(--svg-stroke-width--4px, 4px);
}

.pbgzjtzrn {
  d: path("M20 4v8h8V4zM4 20v8h8v-8z");
}

</style>
