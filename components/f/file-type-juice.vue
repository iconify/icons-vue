<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<ellipse class="ydyu7b0ro"/><circle class="vsjgcxtmh"/><g class="yxh5jgofy"><path class="bhf3vbcol"/><path class="x3fvoacqh"/><path class="fv5q5ib5m"/><path class="nwd0n-bqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-juice" /></template>
<style>
.bhf3vbcol {
  d: path("M15.587 29.235h1.006V2.945h-1.006z");
}

.fv5q5ib5m {
  d: path("m7.155 6.436l-.711.71l18.581 18.599l.712-.711z");
}

.nwd0n-bqf {
  d: path("m25.75 7.161l-.71-.712L6.428 25.02l.71.711z");
}

.vsjgcxtmh {
  cx: 16.018px;
  cy: 16.018px;
  r: 13.516px;
  fill: none;
  stroke: var(--svg-color--ffc108, #ffc108);
  stroke-width: var(--svg-stroke-width--0-976px, 0.976px);
}

.x3fvoacqh {
  d: path("M2.945 15.585v1.006l26.29.005V15.59z");
}

.ydyu7b0ro {
  cx: 16px;
  cy: 16.054px;
  fill: var(--svg-color--fce494, #fce494);
  rx: 13.163px;
  ry: 13.109px;
}

.yxh5jgofy {
  fill: var(--svg-color--ffc108, #ffc108);
}

</style>
