<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="hkwkpqb8c"/><path class="is810fyzh"/><circle class="nfmwr5s8i"/><path class="yp2v-xtzv"/><circle class="tv2usccad"/><path class="df3b3u06h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-julia" /></template>
<style>
.df3b3u06h {
  fill: var(--svg-color--9558b2, #9558b2);
  d: path("M23.691 28.9A6.309 6.309 0 1 1 30 22.592a6.316 6.316 0 0 1-6.309 6.308m0-11.719a5.41 5.41 0 1 0 5.41 5.41a5.416 5.416 0 0 0-5.41-5.409Z");
}

.hkwkpqb8c {
  cx: 8.309px;
  cy: 22.592px;
  r: 5.86px;
  fill: var(--svg-color--d5635c, #d5635c);
}

.is810fyzh {
  fill: var(--svg-color--cb3c33, #cb3c33);
  d: path("M8.309 28.9a6.309 6.309 0 1 1 6.309-6.309A6.316 6.316 0 0 1 8.309 28.9m0-11.719a5.41 5.41 0 1 0 5.41 5.41a5.416 5.416 0 0 0-5.41-5.409Z");
}

.nfmwr5s8i {
  cx: 16px;
  cy: 9.408px;
  r: 5.86px;
  fill: var(--svg-color--60ad51, #60ad51);
}

.tv2usccad {
  cx: 23.691px;
  cy: 22.592px;
  r: 5.86px;
  fill: var(--svg-color--aa79c1, #aa79c1);
}

.yp2v-xtzv {
  fill: var(--svg-color--389826, #389826);
  d: path("M16 15.717a6.309 6.309 0 1 1 6.309-6.309A6.316 6.316 0 0 1 16 15.717M16 4a5.41 5.41 0 1 0 5.41 5.41A5.416 5.416 0 0 0 16 4");
}

</style>
