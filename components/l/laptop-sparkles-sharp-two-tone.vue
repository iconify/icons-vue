<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="v045ocb8q"/><path class="c6upwkbge"/><path class="j6wq2e0hx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-sparkles-sharp-two-tone" /></template>
<style>
.c6upwkbge {
  fill: currentColor;
  d: path("M19.5492 2.3739L20.4196 4.5804L22.6261 5.4508C22.8518 5.5397 23 5.7576 23 6C23 6.2424 22.8518 6.4603 22.6261 6.5492L20.4196 7.4196L19.5492 9.6261C19.4603 9.8518 19.2424 10 19 10C18.7576 10 18.5397 9.8518 18.4508 9.6261L17.5804 7.4196L15.3739 6.5492C15.1482 6.4603 15 6.2424 15 6C15 5.7576 15.1482 5.5397 15.3739 5.4508L17.5804 4.5804L18.4508 2.3739C18.5397 2.1482 18.7576 2 19 2C19.2424 2 19.4603 2.1482 19.5492 2.3739Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j6wq2e0hx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.8433 9.2337L14.3873 10.6127L15.7663 11.1567C15.9074 11.2123 16 11.3485 16 11.5C16 11.6515 15.9074 11.7877 15.7663 11.8433L14.3873 12.3873L13.8433 13.7663C13.7877 13.9074 13.6515 14 13.5 14C13.3485 14 13.2123 13.9074 13.1567 13.7663L12.6127 12.3873L11.2337 11.8433C11.0926 11.7877 11 11.6515 11 11.5C11 11.3485 11.0926 11.2123 11.2337 11.1567L12.6127 10.6127L13.1567 9.2337C13.2123 9.0926 13.3485 9 13.5 9C13.6515 9 13.7877 9.0926 13.8433 9.2337Z");
  stroke: none;
}

.v045ocb8q {
  d: path("M4 17L4 5L13 5M20 12L20 17M2 17L22 17L22 21L2 21L2 17Z");
}

</style>
