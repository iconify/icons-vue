<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="en0lv7bqg"/><path clip-rule="evenodd" class="hhie0cw1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-left-right-ellipsis-fill" /></template>
<style>
.en0lv7bqg {
  d: path("M7 7L2 12L7 17M17 7L22 12L17 17");
}

.hhie0cw1c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 12C9 12.552 8.552 13 8 13C7.448 13 7 12.552 7 12C7 11.448 7.448 11 8 11C8.552 11 9 11.448 9 12ZM13 12C13 12.552 12.552 13 12 13C11.448 13 11 12.552 11 12C11 11.448 11.448 11 12 11C12.552 11 13 11.448 13 12ZM17 12C17 12.552 16.552 13 16 13C15.448 13 15 12.552 15 12C15 11.448 15.448 11 16 11C16.552 11 17 11.448 17 12Z");
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
