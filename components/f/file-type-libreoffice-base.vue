<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGQNDwFcGl" x1="4" x2="28" y1="31" y2="1" gradientUnits="userSpaceOnUse"><stop offset="0" class="k8ae25bkl"/><stop offset="1" class="ds2fjkbqy"/></linearGradient></defs><g class="d2kvgvbvc"><path fill="url(#SVGQNDwFcGl)" transform="translate(2 2)scale(.875)" class="v6qbtcbjh"/><g class="zffhjno0y"><path class="y7nzi9tng"/><path class="ck4pcsb0s"/></g><path class="d24hddtwb"/><path class="rg77d3bot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-libreoffice-base" /></template>
<style>
.ck4pcsb0s {
  fill-opacity: var(--svg-fill-opacity--0-201, 0.201);
  d: path("M19.5 2h1.225l6.65 6.65v1.225z");
}

.d24hddtwb {
  fill: var(--svg-color--fa9bfd, #fa9bfd);
  d: path("M12.5 13.375a3.5.875 0 0 0-3.5.875v.875a3.5.875 0 0 0 3.5.875a3.5.875 0 0 0 3.5-.875v-.875a3.5.875 0 0 0-3.5-.875M9 16v1.75a3.5.875 0 0 0 3.5.875a3.5.875 0 0 0 3.5-.875V16a3.5.875 0 0 1-3.5.875A3.5.875 0 0 1 9 16m0 2.625v1.75a3.5.875 0 0 0 3.5.875a3.5.875 0 0 0 3.5-.875v-1.75a3.5.875 0 0 1-3.5.875a3.5.875 0 0 1-3.5-.875m0 2.625V23a3.5.875 0 0 0 3.5.875A3.5.875 0 0 0 16 23v-1.75a3.5.875 0 0 1-3.5.875A3.5.875 0 0 1 9 21.25");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.ds2fjkbqy {
  stop-color: var(--svg-color--fa51fd, #fa51fd);
}

.k8ae25bkl {
  stop-color: var(--svg-color--7324a9, #7324a9);
}

.rg77d3bot {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M17.75 15.125a.873.873 0 0 0-.875.875v7c0 .485.39.875.875.875h4.375c.485 0 .875-.39.875-.875v-7a.873.873 0 0 0-.875-.875zm0 .875h1.75v1.75h-1.75zm2.625 0h1.75v1.75h-1.75zm-2.625 2.625h1.75v1.75h-1.75zm2.625 0h1.75v1.75h-1.75zM17.75 21.25h1.75V23h-1.75zm2.625 0h1.75V23h-1.75z");
}

.v6qbtcbjh {
  d: path("M7 0C4.784 0 3 1.784 3 4v24c0 2.216 1.784 4 4 4h18c2.216 0 4-1.784 4-4V12L17 0zm13 0l9 9V0z");
}

.y7nzi9tng {
  fill-opacity: var(--svg-fill-opacity--0-199, 0.199);
  d: path("M4.625 25.625v.875c0 1.939 1.561 3.5 3.5 3.5h15.75c1.939 0 3.5-1.561 3.5-3.5v-.875c0 1.939-1.561 3.5-3.5 3.5H8.125a3.49 3.49 0 0 1-3.5-3.5");
}

.zffhjno0y {
  stroke-linecap: square;
}

</style>
