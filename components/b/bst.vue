<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z9yu8bbhl"/><path class="ars2wrb9t"/><path class="vb4jmv39s"/><path class="d4xjeibjb"/><path class="bcbjgg4jb"/><path class="odno8l0ec"/><path class="u3uyg49xt"/><path class="hz4i0zb0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bst" /></template>
<style>
.ars2wrb9t {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M19.875 12A7.875 7.875 0 0 0 12 4.125V3a9 9 0 0 1 9 9a9 9 0 0 1-9 9v-1.125A7.875 7.875 0 0 0 19.875 12M9.21 4.634a7.9 7.9 0 0 0-2.6 1.625l-.77-.82a9 9 0 0 1 2.972-1.857z");
}

.bcbjgg4jb {
  fill: var(--svg-color--88743c, #88743c);
  d: path("M15.375 12A3.375 3.375 0 0 0 12 8.625V7.5a4.5 4.5 0 0 1 4.5 4.5z");
}

.d4xjeibjb {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M17.225 9.914a5.6 5.6 0 0 0-1.239-1.881l.797-.794a6.8 6.8 0 0 1 1.486 2.257zM6.375 12a5.625 5.625 0 1 0 11.25 0h1.125a6.75 6.75 0 0 1-13.5 0z");
}

.ft5dv1b6b {
  fill: none;
}

.hz4i0zb0r {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M13.125 12A1.124 1.124 0 0 0 12 10.875V9.75a2.25 2.25 0 1 1 0 4.5v-1.125A1.125 1.125 0 0 0 13.125 12");
}

.odno8l0ec {
  fill: var(--svg-color--ffbc00, #ffbc00);
  d: path("M12 8.625a3.375 3.375 0 1 0 0 6.75V16.5a4.5 4.5 0 1 1 0-9zm1.467 6.415a3.4 3.4 0 0 0 1.407-1.27l.957.59a4.5 4.5 0 0 1-1.873 1.692z");
}

.u3uyg49xt {
  fill: var(--svg-color--88743c, #88743c);
  d: path("M12 10.875A1.125 1.125 0 0 0 10.875 12H9.75a2.25 2.25 0 1 1 4.5 0h-1.125A1.124 1.124 0 0 0 12 10.875");
}

.vb4jmv39s {
  fill: var(--svg-color--88743c, #88743c);
  d: path("M12 6.375A5.625 5.625 0 0 0 6.375 12H5.25A6.75 6.75 0 0 1 12 5.25z");
}

.z9yu8bbhl {
  fill: var(--svg-color--88743c, #88743c);
  d: path("M4.125 12A7.875 7.875 0 0 0 12 19.875V21a9 9 0 0 1-9-9z");
}

</style>
