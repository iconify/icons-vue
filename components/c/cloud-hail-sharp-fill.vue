<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="plxrb1b8d"/><path class="pwv-qfb-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-hail-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.plxrb1b8d {
  fill: currentColor;
  d: path("M13.5 17.5C13.5 18.328 12.828 19 12 19C11.172 19 10.5 18.328 10.5 17.5C10.5 16.672 11.172 16 12 16C12.828 16 13.5 16.672 13.5 17.5ZM8.5 20.5C8.5 21.328 7.828 22 7 22C6.172 22 5.5 21.328 5.5 20.5C5.5 19.672 6.172 19 7 19C7.828 19 8.5 19.672 8.5 20.5ZM18.5 20.5C18.5 21.328 17.828 22 17 22C16.172 22 15.5 21.328 15.5 20.5C15.5 19.672 16.172 19 17 19C17.828 19 18.5 19.672 18.5 20.5Z");
  stroke: none;
}

.pwv-qfb-t {
  d: path("M4.5 16.753L4 16.464C2.762 15.75 2 14.429 2 13C2 10.791 3.791 9 6 9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9C20.209 9 22 10.791 22 13C22 14.429 21.238 15.75 20 16.464L19.5 16.753");
}

</style>
