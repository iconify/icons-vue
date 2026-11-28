<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l9y-4lbbs"/><path clip-rule="evenodd" class="m15_xfbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:diamond-nodes-duotone" /></template>
<style>
.l9y-4lbbs {
  stroke-opacity: 0.4;
  d: path("M13.4142 5.414L18.5858 10.586M18.5858 13.414L13.4142 18.586M10.5858 18.586L5.4142 13.414M5.4142 10.586L10.5858 5.414");
}

.m15_xfbta {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.1213 6.121C13.5795 6.663 12.8282 7 12 7C10.3431 7 9 5.657 9 4C9 2.343 10.3431 1 12 1C13.6569 1 15 2.343 15 4C15 4.828 14.6631 5.58 14.1213 6.121ZM17.8787 14.121C17.3369 13.58 17 12.828 17 12C17 10.343 18.3431 9 20 9C21.6569 9 23 10.343 23 12C23 13.657 21.6569 15 20 15C19.1718 15 18.4205 14.663 17.8787 14.121ZM14.1213 22.121C13.5795 22.663 12.8282 23 12 23C10.3431 23 9 21.657 9 20C9 18.343 10.3431 17 12 17C13.6569 17 15 18.343 15 20C15 20.828 14.6631 21.58 14.1213 22.121ZM6.1213 14.121C5.5795 14.663 4.8282 15 4 15C2.3431 15 1 13.657 1 12C1 10.343 2.3431 9 4 9C5.6569 9 7 10.343 7 12C7 12.828 6.6631 13.58 6.1213 14.121Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
