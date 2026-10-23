<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hqfg82b6w"/><g transform="translate(.05 .05)"><rect transform="translate(4.766 5.641)scale(.29172)" class="pmcd8njsz"/><circle class="bqcz3zbya"/><circle class="jrfzc0hwl"/><circle class="n3zee7bgu"/><path class="l62m4p85x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-frontend-opened" /></template>
<style>
.bqcz3zbya {
  cx: 25.281px;
  cy: 15px;
  r: 1.281px;
  fill: var(--svg-color--1c7de6, #1c7de6);
}

.hqfg82b6w {
  fill: var(--svg-color--78bafd, #78bafd);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.jrfzc0hwl {
  cx: 21.843px;
  cy: 15px;
  r: 1.281px;
  fill: var(--svg-color--1c7de6, #1c7de6);
}

.l62m4p85x {
  fill: var(--svg-color--1c7de6, #1c7de6);
  d: path("M12 18h14.541v9H12z");
}

.n3zee7bgu {
  cx: 18.281px;
  cy: 15px;
  r: 1.281px;
  fill: var(--svg-color--1c7de6, #1c7de6);
}

.pmcd8njsz {
  width: 67.058px;
  height: 60.202px;
  x: 16.015px;
  y: 19.872px;
  fill: var(--svg-color--9bc6f4, #9bc6f4);
  stroke: var(--svg-color--1c7de6, #1c7de6);
  stroke-width: var(--svg-stroke-width--6-508px, 6.508px);
  rx: 5.748px;
  ry: 5.644px;
}

</style>
