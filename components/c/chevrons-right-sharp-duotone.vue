<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="apnwk70fe"/><path class="ukdu5oalo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-right-sharp-duotone" /></template>
<style>
.apnwk70fe {
  stroke-opacity: 0.4;
  d: path("M5.7071 17.2929L11 12L5.7071 6.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ukdu5oalo {
  d: path("M12.7071 17.2929L18 12L12.7071 6.7071");
}

</style>
