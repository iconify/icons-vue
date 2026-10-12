<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r40swgbha"/><path class="cxmqm5bal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kelp-forest-sharp" /></template>
<style>
.cxmqm5bal {
  d: path("m6.5 17l2.2-.13L9.9 15l-2.2.13zm0-5.5L5.3 9.63L3.1 9.5l1.2 1.87zm0-4l2.2-.13L9.9 5.5l-2.2.13zm11 10l2.2-.13l1.2-1.87l-2.2.13zm0-5l-1.2-1.87l-2.2-.13l1.2 1.87zm-5.5 5l2.2-.13l1.2-1.87l-2.2.13zm0-5.5l-1.2-1.87L8.6 10l1.2 1.87zm-9.25 9.25h18.5");
}

.r40swgbha {
  d: path("M6.5 20.5c-.75-3 .75-5.5 0-8.5s.75-4 0-6.5m11 15c.75-3-.75-5.5 0-8.5s-.75-1.75 0-3M12 20.5c-.75-3.5.75-6.5 0-10s.75-4.5 0-7.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
