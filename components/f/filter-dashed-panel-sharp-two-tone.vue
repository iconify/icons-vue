<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jh2d-y0fg"/><path class="jd6b5abzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:filter-dashed-panel-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jd6b5abzc {
  d: path("M3 7L3 3L7 3M9 3L14 3M20 8L20 3L16 3M8 20L3 20L3 16M3 9L3 14M11.0009 11L20.9991 11L18 15.5001L18 19.5L14 20.9994L14 15.5001Z");
}

.jh2d-y0fg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 10L20.9991 10C21.5514 10 21.9991 10.4477 21.9991 11C21.9991 11.1974 21.9407 11.3903 21.8312 11.5546L19 15.8028L19 19.5C19 19.9169 18.7414 20.29 18.351 20.4364L14.351 21.9358C14.2388 21.9778 14.1199 21.9994 14 21.9994C13.4477 21.9994 13 21.5517 13 20.9994L13 15.8028L10.1688 11.5546C10.0593 11.3903 10.0009 11.1974 10.0009 11C10.0009 10.4477 10.4486 10 11.0009 10Z");
  stroke: none;
}

</style>
