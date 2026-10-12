<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yqq33acfw"/><path class="ec5d8b3jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bedouin-tent-sharp" /></template>
<style>
.ec5d8b3jg {
  d: path("m10.08 18.01l.84-5.27l.08-.49h2l.08.49l.84 5.27l.08.49h-4zm-7.33 3.24h18.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yqq33acfw {
  d: path("m3.01 17.53l1.73-6.56L5 10l.78-.63l2.44-1.99l.78-.63l.8.6l1.4 1.05l.8.6l.8-.6l1.4-1.05l.8-.6l.78.63l2.44 1.99l.78.63l.26.97l1.73 6.56l.26.97H2.75z");
}

</style>
