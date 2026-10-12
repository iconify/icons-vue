<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vgu78uopy"/><path class="j_6yslzwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:group-chat-sharp" /></template>
<style>
.j_6yslzwm {
  d: path("M10.75 8.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0Zm5.5 0a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0ZM6.5 14l.482-2.25h4.536L12 14m0 0l.482-2.25h4.536L17.5 14");
}

.vgu78uopy {
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
