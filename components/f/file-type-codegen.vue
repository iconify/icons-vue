<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path fill="url(#SVGwLPi2bFe)" clip-rule="evenodd" class="p1_8hzbvm"/><defs><linearGradient id="SVGwLPi2bFe" x1="23.4" x2="44.5" y1="8.8" y2="46.5" gradientTransform="translate(3 1.9)scale(.5231)" gradientUnits="userSpaceOnUse"><stop offset="0" class="nr35t-row"/><stop offset="1" class="k0041qqkk"/></linearGradient></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-codegen" /></template>
<style>
.k0041qqkk {
  stop-color: var(--svg-color--1bcbe2, #1bcbe2);
}

.nr35t-row {
  stop-color: var(--svg-color--e535ab, #e535ab);
}

.p1_8hzbvm {
  fill-rule: evenodd;
  d: path("M3 9.4q0 1.3 1 1.9l.4.1l.3.1h.9a2 2 0 0 0 1.5-2V9l8.6-5l.4-.1h.4L24 8.4q.4-1 1.2-1.6l-7.6-4.3a3 3 0 0 0-2.7 0l-9 5l-.8-.1c-1.1 0-2 1-2 2.1M28.2 11q.8-.7.8-1.6a2.2 2.2 0 0 0-3-2l-.1.1h-.1l-.1.1l-.5.5q-.5.6-.5 1.3q.1 1.6 1.6 2V21q0 .5-.5.7L18.7 26q.7.8.7 1.9l7.6-4.4a3 3 0 0 0 1.3-2.4zm-10 16.9v-.6l-.1-.1V27H18v-.1q-.1 0 0 0l-.1-.1v-.1a2 2 0 0 0-1.8-.9a2 2 0 0 0-1.6.7l-8.2-4.7L6 21v-8.4a3 3 0 0 1-2 0V21q0 1.6 1.4 2.5l8.8 5a2.1 2.1 0 0 0 4-.3zm3.9-17v.2h.1v7.7q0 .3-.3.4l-7.7 4.2h-.5l-5.3-3L8 20v-2h.1l.1-.1l2.2-1v-6h.1l.1-.1l3.7-2l-.1-.5l-.3-.6v-.2q.4-1 2.3-1c1.9 0 2 .4 2.2 1v.2q0 .4-.2.6l-.1.4l3.7 2v.1zm-6.4-2l.1.3l.5 1h.2L17 9zm2-1.2q-.4-.2-1.3-.3q-1.2 0-1.3.2q.3.2 1.2.3q1.1 0 1.3-.3m-2.3 2.8l-.4-.8l-2.8 1.5l4.3 2.4l4.2-2.4l-2.8-1.5l-.4.8q-.1.6-1 .6c-1 0-1-.2-1.1-.6m.5 4L11.5 12v4.7l4.3 2.4zm-6.7 5.3l4.4 2.4v-.6L9 19zm2.4-.5l2.5 1.4l1.3-.6l-4.3-2.4l-1.3.7zm3 3l6.6-3.7V12l-4.3 2.4v5.9h-.1v.1h-.1l-2.1 1z");
}

</style>
