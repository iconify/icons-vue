<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cvleabchf"/><path class="s8_z00p_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delete-restore" /></template>
<style>
.cvleabchf {
  d: path("M5.5 6.5h13l-1 14h-11Zm-2 0h17M9 6.5v-2c0-.55.45-1 1-1h4c.55 0 1 .45 1 1v2m-3 11V11");
}

.s8_z00p_g {
  d: path("M9.5 13.5L12 11l2.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
