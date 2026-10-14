<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2hv08b3o"/><g class="leo8wkb4p"><circle class="et4298b5l"/><g class="ft5dv1b6b"><ellipse class="qxh54xh-b"/><path class="u7ug2wbrs"/><path class="hgc6hcchg"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-domain" /></template>
<style>
.et4298b5l {
  cx: 20.485px;
  cy: 20.505px;
  r: 9px;
  fill: var(--svg-color--76afff, #76afff);
}

.ft5dv1b6b {
  fill: none;
}

.hgc6hcchg {
  stroke-width: var(--svg-stroke-width--1-03px, 1.03px);
  d: path("M12 23.505h16.97");
}

.leo8wkb4p {
  stroke: var(--svg-color--0f3d7d, #0f3d7d);
}

.qxh54xh-b {
  cx: 20.485px;
  cy: 20.505px;
  rx: 2.5px;
  ry: 9px;
}

.u7ug2wbrs {
  stroke-width: var(--svg-stroke-width--1-033px, 1.033px);
  d: path("M12 17.505h17.085");
}

.x2hv08b3o {
  fill: var(--svg-color--4c8de9, #4c8de9);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

</style>
