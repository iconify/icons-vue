<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr0z4kowf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bunsen-burner-sharp" /></template>
<style>
.xr0z4kowf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c2.25 2.1 3.25 3.8 3.25 5.4a3.25 3.25 0 0 1-6.5 0c0-1.6 1-3.3 3.25-5.4Zm-1.75 15.25V14h3.5v4.25m-8 0h12.5v3H5.75zm8-2.5h4");
}

</style>
