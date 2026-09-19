<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uyi4qziex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:archero" /></template>
<style>
.uyi4qziex {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.21 37.79l24.64-24.64M42.5 5.5l-12.64 4.71l5.26 2.67l2.67 5.26zm0 35.41c-1.09 1.87-4.34 1.57-4.34 1.57c1.2-8.14.33-18.07-7.12-25.52S13.66 8.64 5.52 9.84c0 0-.3-3.25 1.57-4.34m3.12 32.29H5.5m7.57-2.86H8.36m4.71 4.71v-4.71m-2.86 7.57v-4.71");
}

</style>
