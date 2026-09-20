<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="yp8lfkb4l"><ellipse class="wxfyecbjg"/><ellipse transform="rotate(-66)" class="ly87scc6a"/><ellipse transform="rotate(66)" class="jyh6nzbko"/><circle class="ftgcdn_po"/><g class="yikj7jbzz"><circle class="uxcqtzbip"/><circle class="fc29076ss"/><circle class="ojc8knb_c"/><circle class="mgc37kb1g"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-atom" /></template>
<style>
.fc29076ss {
  cx: 16px;
  cy: 4.94px;
  r: 2.52px;
}

.ftgcdn_po {
  cx: 16px;
  cy: 17.26px;
  r: 12.32px;
  stroke: var(--svg-color--4b541f, #4b541f);
}

.jyh6nzbko {
  cx: 22.28px;
  cy: -7.6px;
  stroke: var(--svg-color--80a3cf, #80a3cf);
  rx: 1.68px;
  ry: 12.32px;
}

.ly87scc6a {
  cx: -9.26px;
  cy: 21.64px;
  stroke: var(--svg-color--e1d85d, #e1d85d);
  rx: 1.68px;
  ry: 12.32px;
}

.mgc37kb1g {
  cx: 27.2px;
  cy: 22.3px;
  r: 2.52px;
}

.ojc8knb_c {
  cx: 4.8px;
  cy: 22.3px;
  r: 2.52px;
}

.uxcqtzbip {
  cx: 16px;
  cy: 17.26px;
  r: 3.64px;
  fill: var(--svg-color--80a3cf, #80a3cf);
}

.wxfyecbjg {
  cx: 16px;
  cy: 17.26px;
  stroke: var(--svg-color--66899a, #66899a);
  rx: 1.68px;
  ry: 12.32px;
}

.yikj7jbzz {
  fill: var(--svg-color--66899a, #66899a);
  stroke: var(--svg-color--fff, #fff);
}

.yp8lfkb4l {
  fill: none;
  stroke-width: var(--svg-stroke-width--0-56px, 0.56px);
}

</style>
