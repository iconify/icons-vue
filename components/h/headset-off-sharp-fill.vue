<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mi3dc7fdt"/><path class="ngv-p-37v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mi3dc7fdt {
  fill: currentColor;
  d: path("M3 10C3 8.4812 4.4812 7 6 7L8 7C8.5523 7 9 7.4477 9 8L9 18C9 18.5523 8.5523 19 8 19L6 19C4.4812 19 3 17.5188 3 16L3 10ZM18 18L18 19L16 19C15.4477 19 15 18.5523 15 18L15 16L16 16L18 18ZM15 11.3431L15 8C15 7.4477 15.4477 7 16 7L18 7C19.5188 7 21 8.4812 21 10L21 15.3431L19.5858 15.3431L15.5858 11.3431L15 11.3431Z");
  stroke: none;
}

.ngv-p-37v {
  d: path("M4 11L4 10C4 8.3017 4.5292 6.7269 5.4317 5.4317M7.3576 3.3661L8.4739 2.817C9.5376 2.2938 10.7345 2 12 2C16.4183 2 20 5.5817 20 10L20 11M18 18L18 22L11 22M1.7071 1.7071L22.2929 22.2929");
}

</style>
