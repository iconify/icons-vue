<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcdtt4fxs"/><path class="g2-sxwbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-hoop-ball" /></template>
<style>
.g2-sxwbze {
  d: path("m9.5 14l2.5 4.5l2.5-4.5");
}

.hcdtt4fxs {
  d: path("M7.75 6.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM3.5 14h17M6 14l2.25 7.5h7.5L18 14M12 2.5V11M7.75 6.75h8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
