<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w5iq2abwt"/><path class="v4ndkyb6h"/><path class="gg2j7q4jn"/><path class="nc750bnnc"/><path class="gj-9zftfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:burger-line-duotone" /></template>
<style>
.gg2j7q4jn {
  d: path("M12 8.34998H12.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gj-9zftfr {
  d: path("M4.40078 11.65H19.6008C20.4845 11.65 21.2008 12.3663 21.2008 13.25C21.2008 14.1337 20.4845 14.85 19.6008 14.85H4.40078C3.51708 14.85 2.80078 14.1337 2.80078 13.25C2.80078 12.3663 3.51708 11.65 4.40078 11.65Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nc750bnnc {
  d: path("M15 9.34998H15.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v4ndkyb6h {
  d: path("M9 9.25H9.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w5iq2abwt {
  d: path("M4 11.65C4 8.05001 7.2 5.95001 12 5.95001C16.8 5.95001 20 8.05001 20 11.65M4 14.85V16.05C4 17.35 5.2 18.05 7.3 18.05H16.7C18.8 18.05 20 17.35 20 16.05V14.85");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
