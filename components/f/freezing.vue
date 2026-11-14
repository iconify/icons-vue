<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ankm3-tam"/><path class="ilr02kbgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freezing" /></template>
<style>
.ankm3-tam {
  d: path("m13.064 18.058l-1.277.718q-.147.083-.303.146t-.319.105q-.163.043-.33.065q-.167.021-.335.021t-.335-.021t-.33-.065q-.163-.042-.319-.105t-.303-.146l-5.375-3.023q-.152-.085-.291-.19q-.139-.104-.263-.226t-.23-.259q-.107-.138-.195-.288t-.155-.31t-.113-.328t-.068-.341t-.023-.346v-4.93q0-.174.023-.346q.023-.173.068-.341q.046-.167.113-.328q.067-.16.155-.31t.195-.288q.106-.137.23-.259t.263-.226q.139-.105.291-.19l5.375-3.023q.147-.083.303-.146t.319-.105t.33-.065q.167-.021.335-.021t.335.021t.33.065q.163.042.319.105t.303.146l5.375 3.023q.152.085.291.19q.139.104.263.226t.23.259q.107.138.195.288t.155.31q.067.161.113.328q.045.168.068.341q.023.172.023.346v3.483");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilr02kbgm {
  d: path("m2.5 7l8 4.5l8-4.5m-8 4.5v8m7.5-4.75v6.5m-2.75-5l5.5 3.5m-5.5 0l5.5-3.5");
}

</style>
