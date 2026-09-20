<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="wn2mapiuw"/><path class="yd3xadcxk"/><path class="wn0icwbbj"/><path class="jho5fpb_e"/><path class="g0ou9gbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:figma" /></template>
<style>
.g0ou9gbee {
  fill: var(--svg-color--1abcfe, #1abcfe);
  d: path("M256 192c0 35.328-28.672 64-64 64s-64-28.672-64-64s28.672-64 64-64s64 28.672 64 64");
}

.jho5fpb_e {
  fill: var(--svg-color--ff7262, #ff7262);
  d: path("M128 0h64c35.328 0 64 28.672 64 64s-28.672 64-64 64h-64z");
}

.wn0icwbbj {
  fill: var(--svg-color--f24e1e, #f24e1e);
  d: path("M0 64C0 28.672 28.672 0 64 0h64v128H64C28.672 128 0 99.328 0 64");
}

.wn2mapiuw {
  fill: var(--svg-color--0acf83, #0acf83);
  d: path("M64 384c35.328 0 64-28.672 64-64v-64H64c-35.328 0-64 28.672-64 64s28.672 64 64 64");
}

.yd3xadcxk {
  fill: var(--svg-color--a259ff, #a259ff);
  d: path("M0 192c0-35.328 28.672-64 64-64h64v128H64c-35.328 0-64-28.672-64-64");
}

</style>
