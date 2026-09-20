<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGimcRbe8c" x1="4" x2="28" y1="31" y2="1" gradientUnits="userSpaceOnUse"><stop offset="0" class="qx8weezuw"/><stop offset="1" class="t9juwbbkz"/></linearGradient></defs><g class="d2kvgvbvc"><path fill="url(#SVGimcRbe8c)" transform="translate(2 2)scale(.875)" class="v6qbtcbjh"/><g class="zffhjno0y"><path class="y7nzi9tng"/><path class="ck4pcsb0s"/></g><g transform="translate(2 2)scale(.875)" class="y_9pn2b8h"><path class="xhs9j6brk"/><rect class="wvijz8xis"/><rect class="ns0eb6b-u"/><rect class="n3lulu8av"/></g><path class="q-7oft4fi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-libreoffice-math" /></template>
<style>
.ck4pcsb0s {
  fill-opacity: var(--svg-fill-opacity--0-201, 0.201);
  d: path("M19.5 2h1.225l6.65 6.65v1.225z");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.n3lulu8av {
  width: 4px;
  height: 1px;
  x: 20px;
  y: 24px;
  ry: 0.5px;
}

.ns0eb6b-u {
  width: 4px;
  height: 1px;
  x: 14px;
  y: 24px;
  ry: 0.5px;
}

.q-7oft4fi {
  fill: var(--svg-color--fda8b3, #fda8b3);
  d: path("M17.653 16.005a.88.88 0 0 0-.521.251a.875.875 0 0 0 0 1.238l1.131 1.131l-1.131 1.132a.875.875 0 0 0 0 1.237a.875.875 0 0 0 1.237 0l1.131-1.131l1.132 1.13a.875.875 0 0 0 1.237 0a.875.875 0 0 0 0-1.236l-1.131-1.132l1.131-1.131a.875.875 0 0 0 0-1.238a.875.875 0 0 0-1.237 0L19.5 17.388l-1.131-1.132a.88.88 0 0 0-.716-.25");
  color: #000;
}

.qx8weezuw {
  stop-color: var(--svg-color--c10018, #c10018);
}

.t9juwbbkz {
  stop-color: var(--svg-color--ff5a96, #ff5a96);
}

.v6qbtcbjh {
  d: path("M7 0C4.784 0 3 1.784 3 4v24c0 2.216 1.784 4 4 4h18c2.216 0 4-1.784 4-4V12L17 0zm13 0l9 9V0z");
}

.wvijz8xis {
  width: 4px;
  height: 1px;
  x: 8px;
  y: 24px;
  ry: 0.5px;
}

.xhs9j6brk {
  d: path("M15.191 13L11.5 20.383L9.808 17H8.5a.5.5 0 0 0-.5.5a.5.5 0 0 0 .5.5h.691l2.309 4.617L15.808 14H23.5a.5.5 0 0 0 .5-.5a.5.5 0 0 0-.5-.5z");
  color: #000;
}

.y_9pn2b8h {
  fill: var(--svg-color--fafafa, #fafafa);
}

.y7nzi9tng {
  fill-opacity: var(--svg-fill-opacity--0-199, 0.199);
  d: path("M4.625 25.625v.875c0 1.939 1.561 3.5 3.5 3.5h15.75c1.939 0 3.5-1.561 3.5-3.5v-.875c0 1.939-1.561 3.5-3.5 3.5H8.125a3.49 3.49 0 0 1-3.5-3.5");
}

.zffhjno0y {
  stroke-linecap: square;
}

</style>
