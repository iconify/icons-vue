<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG8P97fbFa)" class="j1omzybxr"/><defs><linearGradient id="SVG8P97fbFa" x1="5.332" x2="18.791" y1="18.567" y2="7.92" gradientUnits="userSpaceOnUse"><stop class="unhl4jb9f"/><stop offset="1" class="l2kdgjbto"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kompete" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j1omzybxr {
  d: path("M3.643 21V3H7.5v7.45L14.65 3h5.708l-7.695 7.81L20.357 21h-5.142l-5.362-7.335L7.5 16.05V21z");
}

.l2kdgjbto {
  stop-color: var(--svg-color--6c0c0d, #6c0c0d);
}

.unhl4jb9f {
  stop-color: var(--svg-color--090909, #090909);
}

</style>
