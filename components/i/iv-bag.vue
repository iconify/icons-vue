<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fxgj-u4sr"/><path class="cxhoxcc8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iv-bag" /></template>
<style>
.cxhoxcc8c {
  fill: currentColor;
  d: path("M13.5 6.5C13.5 7.3284 12.8284 8 12 8C11.1716 8 10.5 7.3284 10.5 6.5C10.5 5.6716 11.1716 5 12 5C12.8284 5 13.5 5.6716 13.5 6.5Z");
  stroke: none;
}

.fxgj-u4sr {
  d: path("M8 2L16 2C17.6569 2 19 3.3431 19 5L19 12C19 14.2091 17.2091 16 15 16L9 16C6.7909 16 5 14.2091 5 12L5 5C5 3.3431 6.3431 2 8 2ZM5 11L19 11M12 16L12 19C12 20.6569 10.6569 22 9 22L7 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
