<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="pjaiepbgj"><g transform="translate(-1.88 1.06)scale(3.97274)" class="k64c2rubo"><rect class="m2n3jmb0n"/><rect class="fzz5a18-p"/><rect class="gdneo7beo"/><rect class="m5yw71b_k"/></g><path class="tiuvz8b2y"/><path class="tk0fgbc_w"/><path class="lsfyt3utf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sitemap" /></template>
<style>
.fzz5a18-p {
  width: 1.77px;
  height: 1.77px;
  x: 3.62px;
  y: 0.64px;
  rx: 0.44px;
  ry: 0.44px;
}

.gdneo7beo {
  width: 1.77px;
  height: 1.77px;
  x: 3.62px;
  y: 5.12px;
  rx: 0.44px;
  ry: 0.44px;
}

.k64c2rubo {
  stroke: var(--svg-color--f16427, #f16427);
  stroke-width: var(--svg-stroke-width--0-23px, 0.23px);
}

.lsfyt3utf {
  d: path("M24.94 15.85h1.99v5.48h-2z");
}

.m2n3jmb0n {
  width: 1.77px;
  height: 1.77px;
  x: 1.12px;
  y: 5.12px;
  rx: 0.44px;
  ry: 0.44px;
}

.m5yw71b_k {
  width: 1.77px;
  height: 1.77px;
  x: 6.12px;
  y: 5.12px;
  rx: 0.44px;
  ry: 0.44px;
}

.pjaiepbgj {
  fill: var(--svg-color--f16427, #f16427);
}

.tiuvz8b2y {
  d: path("M15 10.4h2v11.32h-2zm-9.93 4.94h2v5.92h-2z");
}

.tk0fgbc_w {
  d: path("M26.93 15.07v1.99H5.07v-1.99z");
}

</style>
