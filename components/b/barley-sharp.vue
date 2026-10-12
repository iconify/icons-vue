<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgfvs_bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barley-sharp" /></template>
<style>
.rgfvs_bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.5v5.75M12 4.5c1 1 1 3 0 4c-1-1-1-3 0-4Zm0 6c-2 0-3-1-3-2.75c2 0 3 1 3 2.75Zm0 0c2 0 3-1 3-2.75c-2 0-3 1-3 2.75Zm0 5c-2 0-3-1-3-2.75c2 0 3 1 3 2.75Zm0 0c2 0 3-1 3-2.75c-2 0-3 1-3 2.75ZM9 7.75l-3.5-5m9.5 5l3.5-5m-9.5 10L4.5 7.5M15 12.75l4.5-5.25m-7.5-3V2.75");
}

</style>
