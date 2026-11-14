<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fv0rty4yn"/><path class="d-pjllbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:iv-stand" /></template>
<style>
.d-pjllbkt {
  fill: currentColor;
  d: path("M3.75 21a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm15 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Zm-7.5-.25a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

.fv0rty4yn {
  d: path("M12 3.5V18M7 3.5h10M4.5 20l7.5-2l7.5 2M17 3.5c1.75 0 1.75 3 0 3m-10-3v2m-2.25 0h4.5V12h-4.5ZM7 12v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
