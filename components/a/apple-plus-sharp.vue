<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="k5crvxfsc"/><path class="ixl7wg-yq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:apple-plus-sharp" /></template>
<style>
.ixl7wg-yq {
  d: path("M12 8V5.338L13.25 3.5m1.5 1.75c.4-1.5 1.6-2.4 3.5-2.5c-.25 1.6-1.5 2.5-3.5 2.5Zm-8 7.25v-2.165L8.5 9.65");
}

.k5crvxfsc {
  d: path("M12 8c-1.2-.6-2.6-.5-3.9-.5c-2.8 0-4.85 2.4-4.85 5.9c0 4.4 2.85 7.85 5.35 7.85c1.2 0 1.9-.6 3.4-.6s2.2.6 3.4.6c2.5 0 5.35-4.2 5.35-7.85c0-3.5-2.05-5.9-4.85-5.9c-1.3 0-2.7-.1-3.9.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
