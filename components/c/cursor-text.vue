<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_8hp2bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-text" /></template>
<style>
.i_8hp2bxs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3.5H12.9583M3 8.10055H5.98748M3 12.7011H5.98748M10.2669 10.0807L13.3776 20.1434C13.5147 20.5871 14.1112 20.627 14.3032 20.2053L16.3303 15.7538C16.3829 15.6384 16.4755 15.5473 16.5901 15.4983L20.6934 13.745C21.1183 13.5634 21.0964 12.9379 20.6598 12.7882L10.8992 9.44123C10.513 9.30882 10.1437 9.68231 10.2669 10.0807Z");
}

</style>
