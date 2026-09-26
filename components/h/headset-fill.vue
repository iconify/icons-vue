<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o-rra7bzy"/><path class="b_8b-lbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-fill" /></template>
<style>
.b_8b-lbec {
  d: path("M4 10C4 5.581722 7.581722 2 12 2C16.418278 2 20 5.581722 20 10M18 18C18 20.209139 16.209139 22 14 22H12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-rra7bzy {
  fill: currentColor;
  d: path("M3 10C3 8.343146 4.343146 7 6 7L6 7C7.656854 7 9 8.343146 9 10L9 16C9 17.656854 7.656854 19 6 19L6 19C4.343146 19 3 17.656854 3 16ZM15 10C15 8.343146 16.343146 7 18 7L18 7C19.656854 7 21 8.343146 21 10L21 16C21 17.656854 19.656854 19 18 19L18 19C16.343146 19 15 17.656854 15 16Z");
  stroke: none;
}

</style>
