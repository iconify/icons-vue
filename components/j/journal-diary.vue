<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-pb7lboa"/><path class="jr9ofdq4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:journal-diary" /></template>
<style>
.e-pb7lboa {
  d: path("M4 2.5h15.5v19H4Z");
}

.jr9ofdq4a {
  d: path("M15.5 11h6v3.5h-6Zm-8-8.5v19m3-15q1.125-2.25 2.25 0t2.25 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
