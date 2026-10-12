<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n4ef4mq9g"/><path class="tff7oi0jm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-radar-sharp" /></template>
<style>
.n4ef4mq9g {
  d: path("m13.3 3.5l5.41 3.13l1.3.75v9.25l-1.3.75l-5.41 3.12l-1.3.75l-1.3-.75l-5.41-3.12l-1.3-.75V7.37l1.3-.75L10.7 3.5l1.3-.75z");
}

.tff7oi0jm {
  d: path("m12.53 6.78l2.62 2.57l.53.53l.16.73l.76 3.41l.16.73l-.73.15l-3.3.7l-.73.15l-.73-.18l-3.09-.76l-.73-.18l.25-.71l1.02-2.96l.25-.71l.45-.6l2.13-2.8l.45-.6z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
