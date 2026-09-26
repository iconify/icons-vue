<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="umnqrybiq"/><path class="hxwbbnbcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-fill" /></template>
<style>
.hxwbbnbcd {
  d: path("M22 17L22 7C22 5.8954 21.1046 5 20 5L4 5C2.8954 5 2 5.8954 2 7L2 17C2 18.1046 2.8954 19 4 19L20 19C21.1046 19 22 18.1046 22 17ZM18 5C18 6.33333 18.8 9 22 9M18 19C18 17.6667 18.8 15 22 15M6 19C6 17.6667 5.2 15 2 15M6 5C6 6.33333 5.2 9 2 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.umnqrybiq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 5L18 5C18 6.33333 18.8 9 22 9L22 15C18.8 15 18 17.6667 18 19L6 19C6 17.6667 5.2 15 2 15L2 9C5.2 9 6 6.33333 6 5ZM15 12C15 10.3431 13.6569 9 12 9C10.3431 9 9 10.3431 9 12C9 13.6569 10.3431 15 12 15C13.6569 15 15 13.6569 15 12ZM13 12C13 12.5523 12.5523 13 12 13C11.4477 13 11 12.5523 11 12C11 11.4477 11.4477 11 12 11C12.5523 11 13 11.4477 13 12Z");
  stroke: none;
}

</style>
