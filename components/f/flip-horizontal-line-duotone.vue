<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qggxhn8go"/><path class="jknwc2bjg"/><path class="slcp8kbwb"/><path class="cjdiyrc3m"/><path class="gf56ieb5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-line-duotone" /></template>
<style>
.cjdiyrc3m {
  d: path("M12 6V2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gf56ieb5g {
  d: path("M12 22V18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jknwc2bjg {
  d: path("M22 5.88641V18.1136C22 19.8158 22 20.6669 21.4576 20.946C20.9152 21.2251 20.2226 20.7305 18.8375 19.7411L17.2563 18.6117C16.6404 18.1718 16.3325 17.9518 16.1662 17.6288C16 17.3057 16 16.9273 16 16.1705V7.8296C16 7.07277 16 6.69435 16.1662 6.3713C16.3325 6.04825 16.6404 5.8283 17.2563 5.3884L18.8375 4.25894C20.2226 3.26959 20.9152 2.77491 21.4576 3.05405C22 3.33319 22 4.18426 22 5.88641Z");
}

.qggxhn8go {
  d: path("M2 5.88641V18.1136C2 19.8158 2 20.6669 2.54242 20.946C3.08484 21.2251 3.77738 20.7305 5.16248 19.7411L6.74372 18.6117C7.35957 18.1718 7.6675 17.9518 7.83375 17.6288C8 17.3057 8 16.9273 8 16.1705V7.8296C8 7.07277 8 6.69435 7.83375 6.3713C7.6675 6.04825 7.35957 5.8283 6.74371 5.3884L5.16247 4.25894C3.77738 3.26959 3.08484 2.77491 2.54242 3.05405C2 3.33319 2 4.18426 2 5.88641Z");
}

.slcp8kbwb {
  d: path("M12 14V10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
