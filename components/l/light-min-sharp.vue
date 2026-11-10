<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="unjje161g"/><path clip-rule="evenodd" class="wr4k75jvl"/><path clip-rule="evenodd" class="twgt575gm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:light-min-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.twgt575gm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 10.5C7.5 11.05 7.052 11.5 6.5 11.5C5.948 11.5 5.5 11.05 5.5 10.5C5.5 9.95 5.948 9.5 6.5 9.5C7.052 9.5 7.5 9.95 7.5 10.5ZM18.5 10.5C18.5 11.05 18.052 11.5 17.5 11.5C16.948 11.5 16.5 11.05 16.5 10.5C16.5 9.95 16.948 9.5 17.5 9.5C18.052 9.5 18.5 9.95 18.5 10.5Z");
  stroke: none;
}

.unjje161g {
  d: path("M7 16H17");
}

.wr4k75jvl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 8C13 8.55 12.552 9 12 9C11.448 9 11 8.55 11 8C11 7.45 11.448 7 12 7C12.552 7 13 7.45 13 8ZM23 16C23 16.55 22.552 17 22 17C21.448 17 21 16.55 21 16C21 15.45 21.448 15 22 15C22.552 15 23 15.45 23 16ZM3 16C3 16.55 2.552 17 2 17C1.448 17 1 16.55 1 16C1 15.45 1.448 15 2 15C2.552 15 3 15.45 3 16Z");
  stroke: none;
}

</style>
