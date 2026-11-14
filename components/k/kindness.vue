<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s_qmjqcky"/><path class="e_kwm7bkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kindness" /></template>
<style>
.e_kwm7bkv {
  d: path("m14 16l4.5-2.25a1.5 1.5 0 0 1 1.75 2.5L15 20c-.75.5-1.5.75-2.5.75H3M12 10L8.25 6.5A2.25 2.25 0 0 1 12 4a2.25 2.25 0 0 1 3.75 2.5Z");
}

.s_qmjqcky {
  d: path("M3 14.5h3.5c1.5-1.25 2.75-1.5 4-1.5H14a1.5 1.5 0 0 1 0 3h-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
