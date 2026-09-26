<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pcl3d89qc"/><path class="la7gkwdbc"/><path class="nv0xecb8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:headset-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.la7gkwdbc {
  stroke-opacity: 0.4;
  d: path("M16 11.3431V8H18C19.1046 8 20 8.8954 20 10M20 10V15.34M20 10C20 5.5817 16.4183 2 12 2C10.7345 2 9.5376 2.2938 8.4739 2.817L7.3576 3.3661");
}

.nv0xecb8e {
  d: path("M4 10C4 8.8954 4.8954 8 6 8H8V18H6C4.8954 18 4 17.1046 4 16V10ZM4 10C4 8.3017 4.5292 6.7269 5.4317 5.4317M16 16V18H18V22H11M1.7071 1.7071L22.2929 22.2929");
}

.pcl3d89qc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10C3 8.4812 4.4812 7 6 7H8C8.5523 7 9 7.4477 9 8V18C9 18.5523 8.5523 19 8 19H6C4.4812 19 3 17.5188 3 16V10Z");
  stroke: none;
}

</style>
