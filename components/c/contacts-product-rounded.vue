<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guq8d0b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:contacts-product-rounded" /></template>
<style>
.guq8d0b7g {
  fill: currentColor;
  d: path("M4.625 22q-.4 0-.725-.325t-.325-.725v-2.625q0-2.25 1.4-3.975t3.6-2.2q-1 .7-1.55 1.762t-.55 2.288v4.75q0 .275.075.55t.25.5zM8.3 22q-.425 0-.737-.312t-.313-.738V16.2q0-1.75 1.238-2.975T11.475 12H16.2q1.75 0 2.975 1.225T20.4 16.2v1.6q0 1.75-1.225 2.975T16.2 22zM12 9.9q-1.65 0-2.8-1.15t-1.15-2.8t1.15-2.8T12 2t2.8 1.15t1.15 2.8t-1.15 2.8T12 9.9");
}

</style>
