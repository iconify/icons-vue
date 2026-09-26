<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jfd-47bzo"/><path class="cnlqre7gc"/><path class="f8dnqwb0r"/><path class="vfptp1bvw"/><g transform="matrix(.6 0 0 .6 15.9 13.6)"><path class="aenkokq5o"/><path class="db3l-o_gi"/><ellipse class="v-a3flbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sqlproj" /></template>
<style>
.aenkokq5o {
  fill: var(--svg-color--efeef0, #efeef0);
  stroke: var(--svg-color--efeef0, #efeef0);
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-7px, 2.7px);
  d: path("M6.04 5.9a9.96 3.9 0 0 1 19.92 0v20.2a9.96 3.9 0 0 1-19.92 0z");
}

.cnlqre7gc {
  fill: var(--svg-color--7252aa, #7252aa);
  d: path("M29.35 6.88a1.16 1.16 0 0 0-1.44.13l-.08.08L8.73 25.4l-.08.08a1.16 1.16 0 0 1-1.5.09L2.5 22.1a1.16 1.16 0 0 0 1.57-.17q8.4-9.73 16.77-19.47q.36-.4.9-.4q.34 0 .63.18z");
}

.db3l-o_gi {
  fill: var(--svg-color--ffda44, #ffda44);
  d: path("M8.56 15.26A21 21 0 0 0 16 16.45a21 21 0 0 0 7.44-1.2c1.86-.72 2.52-1.53 2.52-2V9.7a10 10 0 0 1-2.08 1.08a22 22 0 0 1-7.88 1.3a22 22 0 0 1-7.88-1.3A10 10 0 0 1 6.04 9.7v3.55c0 .47.66 1.28 2.52 2m0 6.71a16 16 0 0 0 2.6.74a25 25 0 0 0 4.84.46a25 25 0 0 0 4.84-.46a16 16 0 0 0 2.6-.74c1.86-.73 2.52-1.53 2.52-2v-3.39a11 11 0 0 1-1.69.83A24 24 0 0 1 16 18.74a24 24 0 0 1-8.27-1.35a11 11 0 0 1-1.7-.82v3.39c0 .47.67 1.27 2.53 2M16 30c5.5 0 9.96-1.74 9.96-3.9v-2.83a11 11 0 0 1-1.53.76l-.16.06A24 24 0 0 1 16 25.45a23 23 0 0 1-8.27-1.36l-.16-.06a11 11 0 0 1-1.53-.76v2.84C6.04 28.26 10.5 30 16 30");
}

.f8dnqwb0r {
  fill: var(--svg-color--ae7fe2, #ae7fe2);
  d: path("m29.36 25.04l-6.96 4.64a1.2 1.2 0 0 1-1.52-.2L4.1 9.97a1.16 1.16 0 0 0-1.59-.17l4.64-3.47a1.2 1.2 0 0 1 .7-.23q.47 0 .8.32l.08.08l19.1 18.32l.08.08a1.16 1.16 0 0 0 1.44.13z");
}

.jfd-47bzo {
  fill: var(--svg-color--5e438f, #5e438f);
  d: path("M7.14 25.58L2.51 22.1a1.2 1.2 0 0 1-.46-.92V10.74a1.2 1.2 0 0 1 .46-.92l4.63-3.48a1 1 0 0 0-.3.92v17.4a1 1 0 0 0 .3.92");
}

.v-a3flbov {
  cx: 16px;
  cy: 5.89px;
  fill: var(--svg-color--ffda44, #ffda44);
  rx: 9.96px;
  ry: 3.89px;
}

.vfptp1bvw {
  fill: var(--svg-color--d59dff, #d59dff);
  d: path("M29.87 7.84v16.23a1.2 1.2 0 0 1-.52.97l-6.95 4.64a1.2 1.2 0 0 0 .5-.97V3.21a1.2 1.2 0 0 0-.52-.97l6.97 4.64a1.2 1.2 0 0 1 .52.96");
}

</style>
