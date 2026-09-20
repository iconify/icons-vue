<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w39ko6tkz"/><path class="i15q6ifrs"/><path class="caznxbcdb"/><path class="ag27qibsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevrons-up-down-duotone-regular" /></template>
<style>
.ag27qibsz {
  d: path("m7 15 5 5 5 -5");
}

.caznxbcdb {
  d: path("m7 9 5 -5 5 5");
}

.i15q6ifrs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w39ko6tkz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
