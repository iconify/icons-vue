<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3_ztusms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bottle-refill-station" /></template>
<style>
.r3_ztusms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h18V6H3Zm7.5 11.25v1.5L8 17.75v2.5a1.25 1.25 0 0 0 1.25 1.25h5.5A1.25 1.25 0 0 0 16 20.25v-2.5l-2.5-2.5v-1.5M12 6v2.25M12 11h.01");
}

</style>
