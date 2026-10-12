<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="t_2lkqbxb"><g mask="url(#SVGsZ1vtcCp)"><path class="llr7g47-l"/></g><path class="znwrltusi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bell-star" /></template>
<style>
.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.llr7g47-l {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25a6 6 0 0 0-6 6v3.6c0 .7-.25 1.4-.7 1.95l-.6.75c-.6.75-.1 1.95.9 1.95h12.8c1 0 1.5-1.2.9-1.95l-.6-.75c-.45-.55-.7-1.25-.7-1.95v-3.6a6 6 0 0 0-6-6");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t_2lkqbxb {
  fill: none;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.znwrltusi {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.54 13.92l.83 1.82q.15.32.49.36l2 .22q.34.04.09.28l-1.48 1.35q-.26.24-.19.58l.4 1.96q.07.35-.23.17l-1.75-.99q-.3-.17-.6 0l-1.75.99q-.3.18-.23-.17l.4-1.96q.07-.34-.19-.58l-1.48-1.35q-.25-.24.09-.28l2-.22q.34-.04.49-.36l.83-1.82q.14-.32.28 0");
}

</style>
