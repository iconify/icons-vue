<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGeP5Myl1x)" transform="translate(4.8 2)scale(.09333)"><mask id="SVG5HOavdEo" width="240" height="300" x="0" y="0" maskUnits="userSpaceOnUse"><path class="n8t9ivbfj"/></mask><g mask="url(#SVG5HOavdEo)"><path class="zyupppbkl"/><path class="j81bmwodf"/></g></g><defs><clipPath id="SVGeP5Myl1x"><path class="kh3fznufa"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-opencode" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j81bmwodf {
  fill: var(--svg-color--f1ecec, #f1ecec);
  d: path("M180 60H60v180h120zm60 240H0V0h240z");
}

.kh3fznufa {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h240v300H0z");
}

.n8t9ivbfj {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M240 0H0v300h240z");
}

.zyupppbkl {
  fill: var(--svg-color--4b4646, #4b4646);
  d: path("M180 240H60V120h120z");
}

</style>
