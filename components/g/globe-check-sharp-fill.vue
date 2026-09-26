<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="gcrhrmmun"/><path class="ypxhweb_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:globe-check-sharp-fill" /></template>
<style>
.gcrhrmmun {
  fill: currentColor;
  d: path("M12 1C18.0751 1 23 5.9249 23 12C23 11.4477 22.5523 11 22 11L16.9658 11C16.7774 8.2182 15.8031 5.4794 14.0649 3L9.9351 3C8.1969 5.4793 7.2226 8.2182 7.0342 11L3 11L3 13L7.0342 13C7.2658 16.4205 8.6858 19.7761 11.2529 22.6641C11.4504 22.8863 11.7246 22.998 12 22.998L12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1ZM12 3.5713C13.7801 5.8823 14.7568 8.4349 14.958 11L9.042 11C9.2432 8.4349 10.2199 5.8823 12 3.5713Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ypxhweb_v {
  d: path("M15.7055 19.2971L18.3333 22L22.1467 15.76");
}

</style>
