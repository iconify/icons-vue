<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="khrb7na_d"/><path class="xzcs0vr8n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-doctor" /></template>
<style>
.khrb7na_d {
  d: path("M4 5.5C4 4.1 5.1 3 6.5 3h11C18.9 3 20 4.1 20 5.5v9c0 1.4-1.1 2.5-2.5 2.5H10l-4.5 3.75v-4C4.6 16.5 4 15.6 4 14.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xzcs0vr8n {
  d: path("M8.5 6v2.5c0 1.75 1.25 3 2.75 3S14 10.25 14 8.5V6m-2.75 5.5v1c0 1.25 1 2 2.25 2s2-1 2-1.75m-1.25-1.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
