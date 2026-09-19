<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d5uom3bvn"/><path class="s33tanbdq"/><rect class="cshyuquvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:googleslides" /></template>
<style>
.cshyuquvg {
  width: 24.143px;
  height: 14.857px;
  x: 12.202px;
  y: 16.126px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.929px;
  ry: 0.929px;
}

.d5uom3bvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.787 8.777h-.01A6.46 6.46 0 0 0 32.73 4.84L10.278 8.508c-.297.046-.604.12-.882.213c-.01.01-.02.01-.02.01m-.641 29.593a6.51 6.51 0 0 0 7.057 3.946l22.453-3.668a7 7 0 0 0 .92-.223");
}

.s33tanbdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.773 15.569c0-2.076 0-3.114.327-3.938a4.64 4.64 0 0 1 2.607-2.607c.824-.327 1.862-.327 3.938-.327h25.257c2.076 0 3.114 0 3.937.326a4.64 4.64 0 0 1 2.608 2.608c.326.824.326 1.862.326 3.938V31.54c0 2.076 0 3.114-.326 3.938a4.64 4.64 0 0 1-2.608 2.608c-.823.326-1.861.326-3.937.326H11.645c-2.076 0-3.114 0-3.938-.326A4.64 4.64 0 0 1 5.1 35.478c-.327-.824-.327-1.862-.327-3.938z");
}

</style>
