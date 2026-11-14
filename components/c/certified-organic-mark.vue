<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6rukgujb"/><path class="mugfj1_vj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:certified-organic-mark" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mugfj1_vj {
  d: path("M8.5 15.5c0-4.5 2.25-7 7-7c0 4.5-2.5 7-7 7m0 0l4-4");
}

.v6rukgujb {
  d: path("m20.625 13l-.319.365a1.75 1.75 0 0 0-.405 1.465l.108.595A1.65 1.65 0 0 1 19 17.25l-.554.221a1.75 1.75 0 0 0-.975.975L17.25 19a1.65 1.65 0 0 1-1.825 1.009l-.595-.108a1.75 1.75 0 0 0-1.465.405l-.365.319a1.52 1.52 0 0 1-2 0l-.365-.319a1.75 1.75 0 0 0-1.465-.405l-.595.108A1.65 1.65 0 0 1 6.75 19l-.221-.554a1.75 1.75 0 0 0-.975-.975L5 17.25a1.65 1.65 0 0 1-1.009-1.825l.108-.595a1.75 1.75 0 0 0-.405-1.465L3.375 13a1.52 1.52 0 0 1 0-2l.319-.365a1.75 1.75 0 0 0 .405-1.465l-.108-.595A1.65 1.65 0 0 1 5 6.75l.554-.221a1.75 1.75 0 0 0 .975-.975L6.75 5a1.65 1.65 0 0 1 1.825-1.009l.595.108a1.75 1.75 0 0 0 1.465-.405L11 3.375a1.52 1.52 0 0 1 2 0l.365.319a1.75 1.75 0 0 0 1.465.405l.595-.108A1.65 1.65 0 0 1 17.25 5l.221.554a1.75 1.75 0 0 0 .975.975L19 6.75a1.65 1.65 0 0 1 1.009 1.825l-.108.595a1.75 1.75 0 0 0 .405 1.465l.319.365a1.52 1.52 0 0 1 0 2");
}

</style>
