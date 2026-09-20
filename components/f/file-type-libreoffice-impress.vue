<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGngmjzbJk" x1="4" x2="28" y1="31" y2="1" gradientUnits="userSpaceOnUse"><stop offset="0" class="rgtnnubui"/><stop offset="1" class="mhra_9blu"/></linearGradient></defs><g class="ywbk9fbil"><path fill="url(#SVGngmjzbJk)" transform="translate(2 2)scale(.875)" class="v6qbtcbjh"/><path class="y7nzi9tng"/><path class="ck4pcsb0s"/><g transform="translate(2 2)scale(.875)" class="y_9pn2b8h"><rect class="bh6f0rn1c"/><rect class="jfzzt-bvu"/><circle class="mojgqt0xn"/><circle class="hbd16l-qs"/><circle class="ubjojxbgg"/><rect class="vkgs2zblf"/><rect class="fczdzubeo"/><rect class="sg9l1kbht"/></g><path class="fsexbfbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-libreoffice-impress" /></template>
<style>
.bh6f0rn1c {
  width: 16px;
  height: 1px;
  x: 8px;
  y: 13px;
  ry: 0.5px;
}

.ck4pcsb0s {
  fill-opacity: var(--svg-fill-opacity--0-201, 0.201);
  d: path("M19.5 2h1.225l6.65 6.65v1.225z");
}

.fczdzubeo {
  width: 5px;
  height: 1px;
  x: 10px;
  y: 21px;
  ry: 0.5px;
}

.fsexbfbdg {
  fill: var(--svg-color--fecfb5, #fecfb5);
  d: path("M16.875 18.625A.873.873 0 0 0 16 19.5V23c0 .485.39.875.875.875h5.25c.485 0 .875-.39.875-.875v-3.5a.873.873 0 0 0-.875-.875zm4.744.88a.44.44 0 0 1 .378.123a.44.44 0 0 1 0 .619l-2.06 2.06l-.874-.876l-1.441 1.44a.44.44 0 0 1-.619 0a.44.44 0 0 1 0-.618l2.06-2.06l.875.876l1.44-1.44a.44.44 0 0 1 .241-.124");
}

.hbd16l-qs {
  cx: 8.5px;
  cy: 21.5px;
  r: 0.5px;
}

.jfzzt-bvu {
  width: 12px;
  height: 1px;
  x: 10px;
  y: 15px;
  ry: 0.5px;
}

.mhra_9blu {
  stop-color: var(--svg-color--fe9c45, #fe9c45);
}

.mojgqt0xn {
  cx: 8.5px;
  cy: 19.5px;
  r: 0.5px;
}

.rgtnnubui {
  stop-color: var(--svg-color--d0120d, #d0120d);
}

.sg9l1kbht {
  width: 5px;
  height: 1px;
  x: 10px;
  y: 23px;
  ry: 0.5px;
}

.ubjojxbgg {
  cx: 8.5px;
  cy: 23.5px;
  r: 0.5px;
}

.v6qbtcbjh {
  d: path("M7 0C4.784 0 3 1.784 3 4v24c0 2.216 1.784 4 4 4h18c2.216 0 4-1.784 4-4V12L17 0zm13 0l9 9V0z");
}

.vkgs2zblf {
  width: 5px;
  height: 1px;
  x: 10px;
  y: 19px;
  ry: 0.5px;
}

.y_9pn2b8h {
  fill: var(--svg-color--fafafa, #fafafa);
}

.y7nzi9tng {
  fill-opacity: var(--svg-fill-opacity--0-199, 0.199);
  d: path("M4.625 25.625v.875c0 1.939 1.561 3.5 3.5 3.5h15.75c1.939 0 3.5-1.561 3.5-3.5v-.875c0 1.939-1.561 3.5-3.5 3.5H8.125a3.49 3.49 0 0 1-3.5-3.5");
}

.ywbk9fbil {
  fill-rule: evenodd;
  stroke-linecap: square;
}

</style>
