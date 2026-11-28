<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="exlknac3d"><path class="dni4dqblb"/><path class="vb2nj7cda"/><path class="v-3nih4lx"/><path class="azj_mkb3h"/><path class="m03rwlbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-prettier" /></template>
<style>
.azj_mkb3h {
  stroke: var(--svg-color--bf85bf, #bf85bf);
  d: path("M14.7 8.06h5.29m-17.2 5.3h6.62m9.26 5.29h3.96M2.82 21.29h1.31m-1.31 2.65h6.6");
}

.dni4dqblb {
  stroke: var(--svg-color--56b3b4, #56b3b4);
  d: path("M2.83 2.77h15.92M2.83 8.06h9.26m10.55 0h1.31M8.03 10.71h1.32M13.32 16h10.55m-21.2 2.65h5.3m-5.3 7.94h2.65");
}

.exlknac3d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
}

.m03rwlbvj {
  stroke: var(--svg-color--d0d4d8, #d0d4d8);
  d: path("M21.34 2.77h7.94M25.3 5.4h3.97m-2.65 2.65h2.65m-17.2 2.65h3.97m11.92 0h1.32m-17.2 2.64h3.97m11.92 0h1.32M26.65 16h2.65m-3.97 2.65h3.97m-7.94 2.64H24m2.65 0h2.65m-17.2 2.65h2.65m2.65 0h11.92m-17.2 2.65h5.3m2.65 0h1.32m2.64 0h5.3m-17.2 2.64h7.95m2.64 0h6.62");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v-3nih4lx {
  stroke: var(--svg-color--f7b93e, #f7b93e);
  d: path("M9.45 5.41h13.19M2.8 10.71h2.64m13.19 2.64h6.61M6.7 16h3.97M6.7 21.3h11.92M8.06 26.58h1.32");
}

.vb2nj7cda {
  stroke: var(--svg-color--ea5e5e, #ea5e5e);
  d: path("M2.83 5.41h3.96m11.92 5.3h6.61M2.86 16h1.31m6.62 2.65h5.3M2.88 29.2H9.5");
}

</style>
