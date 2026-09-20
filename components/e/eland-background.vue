<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="af9yoac6s"/><path class="fn37g4bmk"/><path class="atl-r91jz"/><path class="sv_wmh2qv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eland-background" /></template>
<style>
.af9yoac6s {
  fill: var(--svg-color--066, #066);
  d: path("M24 0H0v24h24z");
}

.atl-r91jz {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.23 11.301a.1.1 0 0 1-.052.047l-5.154 2.518a.07.07 0 0 1-.063 0l-5.145-2.518a.1.1 0 0 1-.05-.047a9.7 9.7 0 0 1-.56-1.545c0-.017.003-.034.02-.042l5.727-2.148a.1.1 0 0 1 .076 0l5.735 2.135c.008 0 .017.009.017.013a9 9 0 0 1-.556 1.583z");
}

.fn37g4bmk {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.95 6.303l-5.82 2.19a.02.02 0 0 1-.017-.005l-.008-.008v-.013c.859-5.937 10.876-5.962 11.79-.038q.006.062-.05.042l-5.812-2.168a.1.1 0 0 0-.084 0");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sv_wmh2qv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.979 18.42a.04.04 0 0 0 .008-.025a.04.04 0 0 0-.008-.03a58 58 0 0 1-3.082-3.637a15 15 0 0 1-1.078-1.575q-.026-.05.025-.025l4.114 2.008c.03.013.055.013.084 0l4.101-1.996q.09-.045.038.038c-1.158 1.853-2.674 3.58-4.16 5.192a.04.04 0 0 0 0 .055c.253.244.8.888.585 1.255c-.18.307-.636.404-.947.244c-.708-.367 0-1.17.32-1.503");
}

</style>
