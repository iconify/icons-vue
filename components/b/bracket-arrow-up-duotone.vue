<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dq9baqbrc"/><path class="rsfqqzbsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-up-duotone" /></template>
<style>
.dq9baqbrc {
  stroke-opacity: 0.4;
  d: path("M20 12.8907L20 18C20 20.2091 18.2091 22 16 22L8 22C5.7909 22 4 20.2091 4 18L4 12.8907");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rsfqqzbsu {
  d: path("M12 2.7693L12 12.8907M17.5 7.83L12.3686 2.1641C12.1704 1.9453 11.8296 1.9453 11.6314 2.1641L6.5 7.83");
}

</style>
