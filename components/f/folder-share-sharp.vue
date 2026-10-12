<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="l71ptbcpf"/><circle class="p374bcbxq"/><circle class="id0kkljei"/><circle class="u9x99hfmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-share-sharp" /></template>
<style>
.id0kkljei {
  cx: 19.5px;
  cy: 14.75px;
  r: 1.25px;
}

.l71ptbcpf {
  d: path("M11.75 19.25h-9V4.75h7.1l.6.8L11.55 7l.6.8h9.1v4.75m-18.5-1.8h12m1.75 6l2-1.25m-2 2.75l2 1.25");
}

.p374bcbxq {
  cx: 15.25px;
  cy: 17.5px;
  r: 1.5px;
}

.u9x99hfmy {
  cx: 19.5px;
  cy: 20px;
  r: 1.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
