<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zwjgx6-8v"/><path class="wzb_zeqgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-relief" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wzb_zeqgk {
  d: path("M6 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1 10h14m-12-2l-2 2l2 2m10-4l2 2l-2 2");
}

.zwjgx6-8v {
  d: path("M2.5 9.5C4 6.25 6 4.75 8 4.75s4 1.5 5.5 4.75C12 12.75 10 14.25 8 14.25s-4-1.5-5.5-4.75Zm14.25 0a2.25 6.5 0 1 0 4.5 0a2.25 6.5 0 1 0-4.5 0Z");
}

</style>
