<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGghnJBz0x)" class="h1z5r3bea"/><defs><linearGradient id="SVGghnJBz0x" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="l5h6e9i1g"/><stop offset="1" class="oc_pgy7yc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lobstr" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1z5r3bea {
  d: path("M12 21c-4.527 0-7.687-2.777-7.687-6.752c0-3.763 4.297-9.953 9.15-11.248c-1.1 1.098-2.613 2.753-3.455 4.559c-1.195 2.561-1.31 6.47-1.205 6.93l.169.742l.717-.278a8.6 8.6 0 0 0 2.22-1.282q.673-.532 1.245-1.17c1.539-1.708 2.524-3.918 2.684-5.907c2.191 1.463 3.85 4.655 3.85 7.652C19.688 18.225 16.526 21 12 21");
}

.l5h6e9i1g {
  stop-color: var(--svg-color--35b5ce, #35b5ce);
}

.oc_pgy7yc {
  stop-color: var(--svg-color--1a96b2, #1a96b2);
}

</style>
