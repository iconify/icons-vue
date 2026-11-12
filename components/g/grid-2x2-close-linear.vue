<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="duo8u5b0b"/><path class="s6deurbms"/><path class="kt_jy-ber"/><path class="tb-reab7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-close-linear" /></template>
<style>
.duo8u5b0b {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt_jy-ber {
  d: path("M2.00488 11.9951L22.0048 11.9951");
}

.s6deurbms {
  d: path("M12 22L12 2.00003");
}

.tb-reab7h {
  d: path("M15.3791 15.3787L17.5005 17.5M17.5005 17.5L19.6218 19.6213M17.5005 17.5L19.6218 15.3787M17.5005 17.5L15.3791 19.6213");
}

</style>
