<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jgq7bxb2g"/><path class="rfle3nbeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-buffer-tri-state-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jgq7bxb2g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.9789 10.1221L18.4789 13.1221C18.8001 13.2973 19 13.6341 19 14C19 14.3659 18.8001 14.7027 18.4789 14.8779L7.4789 20.8779C7.332 20.958 7.1673 21 7 21C6.4477 21 6 20.5523 6 20L6 8C6 7.4477 6.4477 7 7 7C7.1673 7 7.332 7.042 7.4789 7.1221Z");
  stroke: none;
}

.rfle3nbeh {
  d: path("M1 14L7 14M18 14L23 14M13 3L13 11.2727");
}

</style>
