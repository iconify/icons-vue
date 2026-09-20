<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":239};
const content = `<path class="i8ialsbog"/><ellipse class="ef2d5cb2e"/><path class="wldnby_6z"/><ellipse class="ixc3a2lqw"/><path class="t1tkobbga"/><ellipse class="e_uf52btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-data-studio" /></template>
<style>
.e_uf52btz {
  cx: 224.022px;
  cy: 32.485px;
  fill: var(--svg-color--1a73e8, #1a73e8);
  rx: 31.979px;
  ry: 32.485px;
}

.ef2d5cb2e {
  cx: 224.022px;
  cy: 205.587px;
  fill: var(--svg-color--1a73e8, #1a73e8);
  rx: 31.979px;
  ry: 32.485px;
}

.i8ialsbog {
  fill: var(--svg-color--669df6, #669df6);
  d: path("M224.022 173.159h-92.959c-22.48 0-35.07 15.736-35.07 32.485c0 15.455 10.679 32.484 35.07 32.484h92.959z");
}

.ixc3a2lqw {
  cx: 128.028px;
  cy: 119.036px;
  fill: var(--svg-color--1a73e8, #1a73e8);
  rx: 31.979px;
  ry: 32.485px;
}

.t1tkobbga {
  fill: var(--svg-color--669df6, #669df6);
  d: path("M224.022 0h-92.959c-22.48 0-35.07 15.737-35.07 32.485c0 15.455 10.679 32.485 35.07 32.485h92.959z");
}

.wldnby_6z {
  fill: var(--svg-color--669df6, #669df6);
  d: path("M128.028 86.551H35.07C12.59 86.551 0 102.288 0 119.036c0 15.456 10.678 32.485 35.07 32.485h92.958z");
}

</style>
