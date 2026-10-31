<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qgvhz-bst"/><path class="xk_b8vbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grill-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qgvhz-bst {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.4111 15.7072C13.6227 15.9018 12.8137 16.0002 12.0017 16.0002C10.8943 16.0002 9.7945 15.8172 8.7468 15.4586L6.8605 18.7596L5.1241 17.7674L6.9239 14.6176C4.5285 13.2051 2.8283 10.8601 2.2306 8.1443C2.077 7.4399 1.9996 6.721 2 6C2 5.4477 2.4477 5 3 5L5.5 5L5.5 7L4.0618 7C4.304 8.9339 5.2453 10.7123 6.7083 12L17.2917 12C18.7547 10.7123 19.696 8.9339 19.9382 7L18.5 7L18.5 5L21 5C21.5523 5 22 5.4477 22 6C22.003 8.8305 20.8035 11.5291 18.7003 13.4235C17.9808 14.0735 17.1707 14.6157 16.2953 15.0328L19.1799 22.2584L17.3225 23L16.524 21L7 21L7 19L15.7256 19L14.4111 15.7072Z");
  stroke: none;
}

.xk_b8vbkg {
  d: path("M7 20C7 21.1046 6.1046 22 5 22C3.8954 22 3 21.1046 3 20C3 18.8954 3.8954 18 5 18C6.1046 18 7 18.8954 7 20ZM8.5 10L8.5 8.8028C8.5 7.6273 8.848 6.4781 9.5 5.5C10.1521 4.5219 10.5 3.3727 10.5 2.1972L10.5 1M13.5 10L13.5 8.8028C13.5 7.6273 13.848 6.4781 14.5 5.5C15.1521 4.5219 15.5 3.3727 15.5 2.1972L15.5 1");
}

</style>
