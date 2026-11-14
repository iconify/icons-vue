<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uem51cbps"/><path class="pb4-_3bdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gadget-watch-cover" /></template>
<style>
.pb4-_3bdw {
  d: path("M12 9.5V12l1.5 1");
}

.uem51cbps {
  d: path("M8 6.5h8a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1Zm1 0l.75-4h4.5l.75 4m-6 11l.75 4h4.5l.75-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
