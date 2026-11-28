<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8gbxqb7e"/><path class="hk958zb1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-x-duotone" /></template>
<style>
.c8gbxqb7e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6L19 6L19 19C19 21.2091 17.2091 23 15 23L9 23C6.7909 23 5 21.2091 5 19Z");
  stroke: none;
}

.hk958zb1w {
  d: path("M10 2H14M4 7H20M10 13L14 17M14 13L10 17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
