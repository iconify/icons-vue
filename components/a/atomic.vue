<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG1RwGod7e)" clip-rule="evenodd" class="g182bf8vf"/><defs><linearGradient id="SVG1RwGod7e" x1="3" x2="3" y1="3.5" y2="20.5" gradientUnits="userSpaceOnUse"><stop class="fswko_bmi"/><stop offset="1" class="c-2x1jbnv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atomic" /></template>
<style>
.c-2x1jbnv {
  stop-color: var(--svg-color--1f8efa, #1f8efa);
}

.fswko_bmi {
  stop-color: var(--svg-color--42c1fd, #42c1fd);
}

.ft5dv1b6b {
  fill: none;
}

.g182bf8vf {
  fill-rule: evenodd;
  d: path("M3 20.5L8.341 6.152c.678-1.676 1.942-2.624 3.621-2.651V3.5h.076c1.68.028 2.943.976 3.62 2.652L21 20.5l-3.307-1.128L13.13 7.115c-.278-.678-.599-.922-1.13-.933c-.532.011-.852.255-1.13.933L6.308 19.372zm11.324-5.464a2.28 2.28 0 0 1-2.293 2.27c-1.266 0-2.292-1.017-2.292-2.27s1.026-2.27 2.292-2.27a2.28 2.28 0 0 1 2.293 2.27");
}

</style>
