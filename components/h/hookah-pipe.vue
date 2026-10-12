<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eheei_tep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hookah-pipe" /></template>
<style>
.eheei_tep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.25c2.75 0 4.5 2.4 4.5 4.6a3.4 3.4 0 0 1-3.4 3.4h-2.2a3.4 3.4 0 0 1-3.4-3.4c0-2.2 1.75-4.6 4.5-4.6m-1.9-9h3.8q.6 0 .35.55l-.75 1.65q-.25.55-.85.55h-1.3q-.6 0-.85-.55L9.75 4.8q-.25-.55.35-.55M12 7v6.25m0-2.5c2.25 0 3-2.5 5.25-2.5c1.75 0 3 1.25 3 3.25v3m0 2v2.75");
}

</style>
