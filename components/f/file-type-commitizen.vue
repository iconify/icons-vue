<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vnrqkgbam"/><path class="ep66k5i6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-commitizen" /></template>
<style>
.ep66k5i6j {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M25.05 22s-2.85-2.53-3-2.73a6.73 6.73 0 0 0 0-6.27q.35-.39 2.94-2.82a10.7 10.7 0 0 1 0 11.82ZM22.14 7.29s-2.4 2.65-2.74 3a6.64 6.64 0 0 0-3.28-.86a6.74 6.74 0 1 0 0 13.47a6.7 6.7 0 0 0 3.2-.81c.27.25 1.2 1.24 2.78 3a10.71 10.71 0 1 1 0-17.72Z");
}

.vnrqkgbam {
  fill: var(--svg-color--3385ff, #3385ff);
  fill-rule: evenodd;
  d: path("M16.12 29.76a13.63 13.63 0 1 1 13.62-13.63a13.63 13.63 0 0 1-13.62 13.63");
}

</style>
