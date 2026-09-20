<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="pjaiepbgj"><g transform="translate(-2 .955)scale(3.9999)" class="hwneuincd"><rect class="iaivzbq-f"/><rect class="wandjd64r"/><rect class="pkylttd2t"/><rect class="m9e9rob-w"/></g><path class="n7xp5lbtn"/><path class="dm9xkhblt"/><path class="bttmy5xjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-sitemap" /></template>
<style>
.bttmy5xjf {
  d: path("M25 15.85h2v5.52h-2z");
}

.dm9xkhblt {
  d: path("M27 15.067v2H4.995v-2z");
}

.hwneuincd {
  stroke: var(--svg-color--f16427, #f16427);
  stroke-width: var(--svg-stroke-width--0-234px, 0.234px);
}

.iaivzbq-f {
  width: 1.766px;
  height: 1.766px;
  x: 1.117px;
  y: 5.117px;
  rx: 0.442px;
  ry: 0.442px;
}

.m9e9rob-w {
  width: 1.766px;
  height: 1.766px;
  x: 6.117px;
  y: 5.117px;
  rx: 0.442px;
  ry: 0.442px;
}

.n7xp5lbtn {
  d: path("M15 10.367h2v11.395h-2zM5 15.339h2v5.96H5z");
}

.pjaiepbgj {
  fill: var(--svg-color--f16427, #f16427);
}

.pkylttd2t {
  width: 1.766px;
  height: 1.766px;
  x: 3.617px;
  y: 5.117px;
  rx: 0.442px;
  ry: 0.442px;
}

.wandjd64r {
  width: 1.766px;
  height: 1.766px;
  x: 3.617px;
  y: 0.639px;
  rx: 0.442px;
  ry: 0.442px;
}

</style>
