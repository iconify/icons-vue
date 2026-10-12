<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fm8xkv5wl"/><circle class="o19ergbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cherry-blossom-sharp" /></template>
<style>
.fm8xkv5wl {
  d: path("M9.74 8.12L9.57 4.7l-.05-1.1l.96.54l.56.32L12 5l.96-.54l.56-.32l.96-.54l-.05 1.1l-.17 3.42l-.06 1.1l1.03-.39l3.2-1.22l1.03-.39l-.22 1.08l-.13.63l-.21 1.08l.81.74l.47.44l.81.75l-1.06.28l-3.3.9l-1.06.29l.69.86l2.14 2.66l.69.86l-1.09.13l-.65.07l-1.09.13l-.46 1l-.26.59l-.46 1l-.6-.92l-1.88-2.87L12 16l-.6.92l-1.88 2.87l-.6.92l-.46-1l-.26-.59l-.46-1l-1.09-.13l-.65-.07l-1.09-.13l.69-.86l2.14-2.66l.69-.86l-1.06-.29l-3.3-.9l-1.06-.28l.81-.75l.47-.44l.81-.74l-.21-1.08l-.13-.63l-.22-1.08l1.03.39l3.2 1.22l1.03.39z");
}

.o19ergbhs {
  cx: 12px;
  cy: 12.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
