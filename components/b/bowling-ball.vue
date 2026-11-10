<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xs-57oboh"/><path clip-rule="evenodd" class="r_n222n3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bowling-ball" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r_n222n3a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 7.5C13.5 8.328 12.8284 9 12 9C11.1716 9 10.5 8.328 10.5 7.5C10.5 6.672 11.1716 6 12 6C12.8284 6 13.5 6.672 13.5 7.5ZM18 10.5C18 11.328 17.3284 12 16.5 12C15.6716 12 15 11.328 15 10.5C15 9.672 15.6716 9 16.5 9C17.3284 9 18 9.672 18 10.5ZM12 13.5C12 14.328 11.3284 15 10.5 15C9.6716 15 9 14.328 9 13.5C9 12.672 9.6716 12 10.5 12C11.3284 12 12 12.672 12 13.5Z");
  stroke: none;
}

.xs-57oboh {
  d: path("M22 12C22 17.523 17.5228 22 12 22C6.4772 22 2 17.523 2 12C2 6.477 6.4772 2 12 2C17.5228 2 22 6.477 22 12Z");
}

</style>
