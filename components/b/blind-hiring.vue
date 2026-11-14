<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-5p8gb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blind-hiring" /></template>
<style>
.n-5p8gb-m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.404 4.154q-.63.63-1.052 1.346h11.296q-.422-.716-1.052-1.346Q14.692 2.25 12 2.25T7.404 4.154M4.5 8.25q0-1.5 1.5-1.5h12q1.5 0 1.5 1.5T18 9.75H6q-1.5 0-1.5-1.5m2.904 5.096q-1.053-1.053-1.524-2.347L6 11h12l.12-.001q-.471 1.294-1.524 2.347Q14.692 15.25 12 15.25t-4.596-1.904M3.25 20.25q0-4 8.75-4t8.75 4q0 2-1.75 2H5q-1.75 0-1.75-2");
}

</style>
