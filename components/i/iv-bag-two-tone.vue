<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aa-c0vbmp"/><path class="x35ormbif"/><path clip-rule="evenodd" class="nps1jb41a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iv-bag-two-tone" /></template>
<style>
.aa-c0vbmp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1H16C18.209 1 20 2.7908 20 5V12C20 14.7614 17.761 17 15 17H9C6.239 17 4 14.7614 4 12V5C4 2.7908 5.791 1 8 1H12Z");
  stroke: none;
}

.nps1jb41a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 6.5C13.5 7.3284 12.828 8 12 8C11.172 8 10.5 7.3284 10.5 6.5C10.5 5.6716 11.172 5 12 5C12.828 5 13.5 5.6716 13.5 6.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x35ormbif {
  d: path("M5 11H19M12 16V19C12 20.6569 10.657 22 9 22H7M8 2H16C17.657 2 19 3.3431 19 5V12C19 14.2091 17.209 16 15 16H9C6.791 16 5 14.2091 5 12V5C5 3.3431 6.343 2 8 2Z");
}

</style>
