<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lvbxx0jiq"/><path class="i8trzcc6o"/><path class="i1hkdem9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-hangar" /></template>
<style>
.i1hkdem9o {
  d: path("M8 19h3l2.5-4l2.5 4");
}

.i8trzcc6o {
  d: path("M5.5 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.lvbxx0jiq {
  d: path("M2.5 21.5v-10a9.5 9.5 0 0 1 19 0v10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
