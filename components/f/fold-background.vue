<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r4hbu3bzp"/><path class="n5__6y-hr"/><path class="ru_3f7b2y"/><path class="h6o40wqpl"/><path class="h1p8iyb7e"/><path class="rvl80gb1i"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fold-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h1p8iyb7e {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.308 12.495a5.752 5.752 0 1 0-10.766-2.02A5.73 5.73 0 0 1 9.61 7.492c2.931 0 5.353 2.166 5.703 5.002z");
}

.h6o40wqpl {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.007 14.675a5.6 5.6 0 0 0 1.546-1.956c.34-.78.45-1.55.455-2.396c0-1.2-.35-2.376-1.085-3.332a6 6 0 0 1 .69.255c.19.085.215.095.395.195v9.85a5.1 5.1 0 0 1-2.001.65z");
}

.n5__6y-hr {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.06 8.493a5.6 5.6 0 0 0-2.622 1a5.823 5.823 0 0 0-1.415 8.035a5.637 5.637 0 0 0 8.484.98h-.566c-3.086.03-5.857-2.491-5.937-5.578c-.045-1.645.795-3.281 2.056-4.437");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4hbu3bzp {
  fill: var(--svg-color--0cffff, #0cffff);
  d: path("M24 0H0v24h24z");
}

.ru_3f7b2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.505 15.996c.566.73 1.321 1.075 2.236 1.485c2.927 1.301 6.389.06 7.734-2.766a5.554 5.554 0 0 0-2.861-7.469a6 6 0 0 0-.69-.255a5.45 5.45 0 0 1 1.085 3.427a5.35 5.35 0 0 1-.455 2.301a5.85 5.85 0 0 1-5.298 3.277z");
}

.rvl80gb1i {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.008 9.743c0 1-.25 1.935-.7 2.75q-.075-.65-.301-1.25V6.501c.63.925 1 2.041 1 3.247z");
}

</style>
