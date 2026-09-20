<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="k-h76sbmj"/><path class="e65-1ibek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-livekit" /></template>
<style>
.e65-1ibek {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M7.6 24.4V2H2v28h16.8v-5.6h-5.6Z");
}

.ft5dv1b6b {
  fill: none;
}

.k-h76sbmj {
  fill: var(--svg-color--1fd5f9, #1fd5f9);
  d: path("M18.8 13.2h-5.6v5.6h5.6zm5.6-5.6h-5.6v5.6h5.6zm0 11.2h-5.6v5.6h5.6zM30 2h-5.6v5.6H30zm0 22.4h-5.6V30H30z");
}

</style>
