<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y7ujc-1mk"/><path class="orpkx52xi"/><path class="b-nob7xrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:browser-share" /></template>
<style>
.b-nob7xrl {
  fill: currentColor;
  d: path("M12 14.25v-4.5a4.5 4.5 0 0 1 4.5 4.5Z");
}

.orpkx52xi {
  d: path("M7.5 14.25a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7ujc-1mk {
  d: path("M2.5 2.5h19v19h-19Zm0 4.25h19M5.5 4.5h.01M8 4.5h.01");
}

</style>
