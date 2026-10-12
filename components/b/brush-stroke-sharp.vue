<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8fmft4eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brush-stroke-sharp" /></template>
<style>
.t8fmft4eg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.31 4.75l-1.06-1.06l-.53-.53l-.53.53l-6.72 6.72l-.53.53l-.71-.17l-.7-.18l-.53.53l-.54.53l-.53.53l.53.53l2.83 2.83l.53.53l.53-.53l.53-.54l.53-.53l-.18-.7l-.17-.71l.53-.53l6.72-6.72l.53-.53zm-8.49 11.32l-3.89-3.89c-2.12 2.12-3.88 4.95-3.71 7.6c2.65.17 5.48-1.59 7.6-3.71Z");
}

</style>
