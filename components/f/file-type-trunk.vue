<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="t2tey3b0u"><path class="dmsrl7bps"/><path class="q14k4ob6u"/><path class="a7b4x4p1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-trunk" /></template>
<style>
.a7b4x4p1a {
  d: path("M21.68 16h-3A2.66 2.66 0 0 0 16 13.36a2.65 2.65 0 0 0-1.88.78a2.6 2.6 0 0 0-.78 1.86h-3a5.68 5.68 0 1 1 11.36 0Z");
}

.dmsrl7bps {
  d: path("M16 29.92v-3a11.07 11.07 0 0 0 6.09-1.83A10.95 10.95 0 0 0 23.75 8.3A11 11 0 0 0 6.89 10a10.87 10.87 0 0 0-1.84 6H2a13.83 13.83 0 0 1 2.36-7.73a14 14 0 1 1 19.42 19.29A14.07 14.07 0 0 1 16 29.92");
}

.q14k4ob6u {
  d: path("M9.2 16h-3A9.78 9.78 0 0 1 9 9.08a9.9 9.9 0 0 1 7-2.86v3A6.79 6.79 0 0 0 9.2 16");
}

.t2tey3b0u {
  fill: var(--svg-color--fb6a5b, #fb6a5b);
}

</style>
