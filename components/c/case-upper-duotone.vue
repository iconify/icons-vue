<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g1vrtlxbq"/><path class="spm2nh4gj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-upper-duotone" /></template>
<style>
.g1vrtlxbq {
  stroke-opacity: 0.4;
  d: path("M2 18L3.7857 13L6.0583 6.668C6.3743 5.783 7.6257 5.783 7.9417 6.668L10.2143 13L12 18M10.2143 13H3.7857");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.spm2nh4gj {
  d: path("M21.1 15L19.8091 10.697C19.5412 9.804 18.4588 9.804 18.1909 10.697L16.9 15M21.1 15H16.9M21.1 15L22 18M16.9 15L16 18");
}

</style>
