<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zxvharbjp"/><path class="e94h20adt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-ointment" /></template>
<style>
.e94h20adt {
  d: path("m15.005 3.838l4.243 4.243l-2.829 2.828l-4.242-4.243ZM5.282 12.5l5.304 5.303M14.5 18q3.5-5 7 0q-3.5 5-7 0Zm3.5 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxvharbjp {
  d: path("m2.984 14.445l5.657 5.656l7.778-9.192l-4.242-4.243Z");
}

</style>
