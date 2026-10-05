<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oqfn6rb5d"/><path class="x7d_bfsij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-cog-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oqfn6rb5d {
  stroke-opacity: 0.4;
  d: path("M10.8903 21.9391C5.8896 21.387 2 17.1477 2 12C2 6.4771 6.4771 2 12 2C17.1477 2 21.387 5.8896 21.9391 10.8903M2 12L11 12M10.144 19.4911C8.7147 17.1249 8 14.5625 8 12C8 8.5 9.3333 5 12 2C14.3927 4.6918 15.712 7.7862 15.9578 10.9218");
}

.x7d_bfsij {
  d: path("M20.6667 18C20.6667 19.4728 19.4728 20.6667 18 20.6667C16.5272 20.6667 15.3333 19.4728 15.3333 18C15.3333 16.5272 16.5272 15.3333 18 15.3333C19.4728 15.3333 20.6667 16.5272 20.6667 18ZM20.99 18L23 18M20.1142 20.1142L21.5355 21.5355M18 20.99L18 23M15.8858 20.1142L14.4645 21.5355M15.01 18L13 18M15.8858 15.8858L14.4645 14.4645M18 15.01L18 13M20.1142 15.8858L21.5355 14.4645");
}

</style>
