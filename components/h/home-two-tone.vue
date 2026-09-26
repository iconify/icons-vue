<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m918zyb_f"/><path class="x_-yl4b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-two-tone" /></template>
<style>
.m918zyb_f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.0605 2.7073C11.1795 1.7593 12.8205 1.7593 13.9395 2.7073L20.9395 8.6379L21.0615 8.7483C21.6586 9.3132 22 10.1004 22 10.927L22 19.0002C21.9999 20.657 20.6568 22.0002 19 22.0002L5 22.0002C3.3432 22.0002 2.0001 20.657 2 19.0002L2 10.927C2 10.0454 2.3877 9.208 3.0605 8.6379L10.0605 2.7073Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x_-yl4b2h {
  d: path("M20.2928 9.4009L13.2928 3.4703C12.5468 2.8383 11.4532 2.8383 10.7072 3.4703L3.7072 9.4009C3.2586 9.7809 3 10.339 3 10.9268L3 19C3 20.1046 3.8954 21 5 21L19 21C20.1046 21 21 20.1046 21 19L21 10.9268C21 10.339 20.7414 9.7809 20.2928 9.4009ZM9 21V14H15V21");
}

</style>
