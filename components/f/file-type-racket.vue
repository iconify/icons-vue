<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="pgkmwcbxw"/><path class="gzppumbdc"/><path class="ed14pnb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-racket" /></template>
<style>
.ed14pnb0u {
  fill: var(--svg-color--9f1d20, #9f1d20);
  d: path("M13.995 10.93a24.3 24.3 0 0 0-7.22-5.46a14 14 0 0 0-1.312 19.747a39.6 39.6 0 0 1 8.532-14.287m2.58 3.17A32.65 32.65 0 0 0 9.43 28.365a14.02 14.02 0 0 0 13.3-.089A38.6 38.6 0 0 0 16.575 14.1");
}

.gzppumbdc {
  fill: var(--svg-color--3e5ba9, #3e5ba9);
  d: path("M27.016 24.641a14 14 0 0 0-15.8-21.8c5.684 2.981 13.197 12.708 15.8 21.8");
}

.pgkmwcbxw {
  cx: 16px;
  cy: 16px;
  r: 14px;
  fill: var(--svg-color--fff, #fff);
}

</style>
