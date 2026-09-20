<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGzQnVdbdr" x1="4" x2="28" y1="31" y2="1" gradientUnits="userSpaceOnUse"><stop offset="0" class="bokguvbse"/><stop offset="1" class="pm1v8mp4b"/></linearGradient></defs><g transform="translate(2 2)scale(.875)" class="d2kvgvbvc"><path fill="url(#SVGzQnVdbdr)" class="v6qbtcbjh"/><g class="zffhjno0y"><path class="swvicthoq"/><path class="u2w316omi"/></g><circle class="mnh4qib-d"/><path class="w-zs_2byq"/><path class="zoa3qy99k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-libreoffice-draw" /></template>
<style>
.bokguvbse {
  stop-color: var(--svg-color--cb6d30, #cb6d30);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.mnh4qib-d {
  cx: 12px;
  cy: 17px;
  r: 4px;
  fill: var(--svg-color--fafafa, #fafafa);
}

.pm1v8mp4b {
  stop-color: var(--svg-color--fffb57, #fffb57);
}

.swvicthoq {
  fill-opacity: var(--svg-fill-opacity--0-199, 0.199);
  d: path("M3 27v1c0 2.216 1.784 4 4 4h18c2.216 0 4-1.784 4-4v-1c0 2.216-1.784 4-4 4H7c-2.216 0-4-1.784-4-4");
}

.u2w316omi {
  fill-opacity: var(--svg-fill-opacity--0-201, 0.201);
  d: path("M20 0h1.4L29 7.6V9z");
}

.v6qbtcbjh {
  d: path("M7 0C4.784 0 3 1.784 3 4v24c0 2.216 1.784 4 4 4h18c2.216 0 4-1.784 4-4V12L17 0zm13 0l9 9V0z");
}

.w-zs_2byq {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M18 15c-.554 0-1 .446-1 1v5c0 .554.446 1 1 1h5c.554 0 1-.446 1-1v-5c0-.554-.446-1-1-1zm0 1h5v5h-5z");
}

.zffhjno0y {
  stroke-linecap: square;
}

.zoa3qy99k {
  fill: var(--svg-color--f9e186, #f9e186);
  d: path("m15 16.866l4.196 7.268a.577.577 0 0 1-.5.866h-8.392a.577.577 0 0 1-.5-.866L14 16.866a.577.577 0 0 1 1 0");
}

</style>
