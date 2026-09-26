<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ol5acvbph"/><path class="vwx95215b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-medium-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ol5acvbph {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5H15C17.20914 5 19 6.79086 19 9V15C19 17.20914 17.20914 19 15 19H5C2.79086 19 1 17.20914 1 15V9C1 6.79086 2.79086 5 5 5ZM6 9H6C6.55228 9 7 9.44772 7 10V14C7 14.55228 6.55228 15 6 15H6C5.44772 15 5 14.55228 5 14V10C5 9.44772 5.44772 9 6 9ZM10 9H10C10.55228 9 11 9.44772 11 10V14C11 14.55228 10.55228 15 10 15H10C9.44772 15 9 14.55228 9 14V10C9 9.44772 9.44772 9 10 9Z");
  stroke: none;
}

.vwx95215b {
  d: path("M22 9.5V14.5");
}

</style>
