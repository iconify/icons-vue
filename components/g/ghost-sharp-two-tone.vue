<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ww6ah8bqr"/><path class="r7o18eb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ghost-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r7o18eb7c {
  d: path("M14.5 23V21.78C14.5 20.25 15.745 19 17.281 19C18.335 19 19.298 19.6 19.769 20.54L20 21V10C20 5.58 16.418 2 12 2C7.582 2 4 5.58 4 10V21L4.231 20.54C4.702 19.6 5.665 19 6.719 19C8.255 19 9.5 20.25 9.5 21.78V23M9 8V11M15 8V11M14.5 23V21.5C14.5 20.12 13.381 19 12 19C10.619 19 9.5 20.12 9.5 21.5V23");
}

.ww6ah8bqr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C16.971 1 21 5.03 21 10V21H20L19.105 21.45L18.874 20.98C18.572 20.38 17.956 20 17.281 20C16.298 20 15.5 20.8 15.5 21.78V23H13.5V21.5C13.5 20.67 12.828 20 12 20C11.172 20 10.5 20.67 10.5 21.5V23H8.5V21.78C8.5 20.8 7.702 20 6.719 20C6.044 20 5.428 20.38 5.126 20.98L4.895 21.45L4 21H3V10C3 5.03 7.029 1 12 1Z");
  stroke: none;
}

</style>
