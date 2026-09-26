<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u1qybnbqt"/><path class="ohmw0ccwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:handbag-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ohmw0ccwc {
  d: path("M8 7C8 4.790861 9.790861 3 12 3C14.209139 3 16 4.790861 16 7M7 7L17 7C18.656854 7 20 8.343146 20 10L20 18C20 19.656854 18.656854 21 17 21L7 21C5.343146 21 4 19.656854 4 18L4 10C4 8.343146 5.343146 7 7 7Z");
}

.u1qybnbqt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2C14.376047 2 16.42377 3.67196 16.898979 6L17 6C19.209139 6 21 7.790861 21 10L21 18C21 20.209139 19.209139 22 17 22L7 22C4.790861 22 3 20.209139 3 18L3 10C3 7.790861 4.790861 6 7 6L7.101021 6C7.57623 3.67196 9.623953 2 12 2ZM12 4C10.728715 4 9.595335 4.801615 9.171573 6L14.828427 6C14.404665 4.801615 13.271285 4 12 4Z");
  stroke: none;
}

</style>
