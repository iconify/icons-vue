<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4v-s3bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:growth-plant-sharp" /></template>
<style>
.z4v-s3bxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 13h9.75v4h1.75v4.25H4.75V17H6.5v-4zM6.5 17h11M12 12.25V7m0 1.75c0-2.6-1.9-4.5-4.75-4.5c0 2.6 1.9 4.5 4.75 4.5ZM12 7c0-2.3 1.7-4.25 4.5-4.25C16.5 5.05 14.8 7 12 7Z");
}

</style>
