<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="esd9hfqww"/><path class="futg1bblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-ai" /></template>
<style>
.esd9hfqww {
  d: path("M4.5 3h15a2 2 0 0 1 2 2v10.5a2 2 0 0 1-2 2h-9L6 21v-3.5H4.5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2Z");
}

.futg1bblw {
  d: path("M7 8.5h10v6H7ZM12 6v2.5m-2 3h.01m3.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
