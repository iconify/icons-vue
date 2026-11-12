<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dfv8mxble"/><path class="k66tt2kvs"/><path class="hq-5njbjh"/><path class="ga-ta5brg"/><path class="x-swg81on"/><path class="nttuc_cwh"/><path class="hn7ztyx-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:boombox-linear" /></template>
<style>
.dfv8mxble {
  stroke-linejoin: round;
  d: path("M6 9.5H18");
}

.ga-ta5brg {
  d: path("M11 16C11 17.6569 9.65685 19 8 19C6.34315 19 5 17.6569 5 16C5 14.3431 6.34315 13 8 13C9.65685 13 11 14.3431 11 16Z");
}

.hn7ztyx-j {
  stroke-linejoin: round;
  d: path("M18.1213 13.8787L16.7071 15.2929");
}

.hq-5njbjh {
  d: path("M16 6C16 4.11438 16 3.17157 15.4142 2.58579C14.8284 2 13.8856 2 12 2C10.1144 2 9.17157 2 8.58579 2.58579C8 3.17157 8 4.11438 8 6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k66tt2kvs {
  d: path("M10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C22 19.6569 22 17.7712 22 14C22 10.2288 22 8.34315 20.8284 7.17157C19.6569 6 17.7712 6 14 6H10C6.22876 6 4.34315 6 3.17157 7.17157C2 8.34315 2 10.2288 2 14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22Z");
}

.nttuc_cwh {
  stroke-linejoin: round;
  d: path("M8 13V15");
}

.x-swg81on {
  d: path("M18.1213 18.1213C16.9497 19.2929 15.0503 19.2929 13.8787 18.1213C12.7071 16.9497 12.7071 15.0503 13.8787 13.8787C15.0503 12.7071 16.9497 12.7071 18.1213 13.8787C19.2929 15.0503 19.2929 16.9497 18.1213 18.1213Z");
}

</style>
