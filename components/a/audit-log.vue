<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="saxb5le3t"/><path class="p9k80vbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audit-log" /></template>
<style>
.p9k80vbmd {
  d: path("M15 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm4.25 1.75L21 21");
}

.saxb5le3t {
  d: path("M12.25 21.5H6.5a2 2 0 0 1-2-2v-15a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v7.75M8 7h6m-6 3.5h6M8 14h1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
