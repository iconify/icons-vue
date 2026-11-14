<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mjwjuzb3j"/><path class="y5dcm6b1o"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:listing-expired" /></template>
<style>
.mjwjuzb3j {
  d: path("M12.7 19.5H2.5v-15h19v7.4m0 5.9v.4");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y5dcm6b1o {
  d: path("m5.5 10.5l4-4l4 4v1.486m-.786 4.514H5.5v-6M16 9h3m-3.5 5.75h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

</style>
