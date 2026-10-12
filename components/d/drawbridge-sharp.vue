<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vdy0dhg7o"/><path class="wrvo-9snk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drawbridge-sharp" /></template>
<style>
.vdy0dhg7o {
  d: path("M9.5 20.75V5h2v2h2.75V5h2.25v2h2.75V5h2v16.25H9.5z");
}

.wrvo-9snk {
  d: path("M12.5 21.25v-4.5a2.375 2.375 0 0 1 4.75 0v4.5m-1.875-11v2M6.02 17.93l-2.79.74l-.48.13l.13.48l.32 1.21l.13.48l.48-.13l2.79-.74l.48-.13l-.13-.48l-.32-1.21l-.13-.48zM9.5 9.5l-6.25 9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
