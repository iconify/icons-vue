<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f4sm45bqc"/><path class="jhu6rdbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-agda" /></template>
<style>
.f4sm45bqc {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M8.81 11.03a.6.6 0 0 1-.59.59a.6.6 0 0 1-.57-.59a.6.6 0 0 1 .57-.58a.6.6 0 0 1 .6.58m2.15 0a.6.6 0 0 1-.59.59a.6.6 0 0 1-.58-.59a.6.6 0 0 1 .58-.58a.6.6 0 0 1 .59.58");
}

.jhu6rdbch {
  fill: none;
  stroke: var(--svg-color--d2d2d2, #d2d2d2);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-78px, 0.78px);
  d: path("M24.64 5.2L16 13.84m12.96-6.49l-4.32 4.33m4.31-6.48l-4.31 4.32M13.84 5.2L9.52 9.52M16 5.2l-4.32 4.32m0-4.32l-8.64 8.64h4.31v4.32c0 4.75 3.9 8.64 8.64 8.64s8.64-3.89 8.64-8.64v-4.32l4.31-4.32");
}

</style>
