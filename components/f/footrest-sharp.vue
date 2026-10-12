<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="azos0ojpk"/><path class="g-y2eza8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:footrest-sharp" /></template>
<style>
.azos0ojpk {
  d: path("m4.36 13.35l15.28-2.7l.98-.17l.17.99l.09.48l.17.99l-.98.17l-15.27 2.7l-.98.17l-.18-.98l-.08-.5l-.18-.98z");
}

.g-y2eza8i {
  d: path("m7.07 12.87l8.63-1.52l.98-.17l-.16-.87l-.15-.86l-.99-.17L13.7 9l-.99-.17l-.84-.54l-1.46-.91l-.84-.54l-.98.18l-2.47.43l-.98.18l.17.98l.61 3.45l.17.98zm5.43 1.63v6.75m-4.75 0h9.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
