<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ks_exo5we"/><path class="kn402bclk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-cog-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kn402bclk {
  d: path("M11 18L2 18L2 2L22 2L22 11M2 5L11.2929 9C11.7154 9.2817 12.2846 9.2817 12.7071 9L22 5M20.6667 18C20.6667 19.4728 19.4728 20.6667 18 20.6667C16.5272 20.6667 15.3333 19.4728 15.3333 18C15.3333 16.5272 16.5272 15.3333 18 15.3333C19.4728 15.3333 20.6667 16.5272 20.6667 18ZM20.99 18L23 18M20.1142 20.1142L21.5355 21.5355M18 20.99L18 23M15.8858 20.1142L14.4645 21.5355M15.01 18L13 18M15.8858 15.8858L14.4645 14.4645M18 15.01L18 13M20.1142 15.8858L21.5355 14.4645");
}

.ks_exo5we {
  fill: currentColor;
  d: path("M5 2L19 2C20.6569 2 22 3.3431 22 5L12.7071 9C12.2846 9.2817 11.7154 9.2817 11.2929 9L2 5C2 3.3431 3.3432 2 5 2Z");
  stroke: none;
}

</style>
