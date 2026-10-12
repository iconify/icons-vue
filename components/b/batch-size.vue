<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve6x304pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:batch-size" /></template>
<style>
.ve6x304pa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25v5.5a2.5 2.5 0 0 0 2.5 2.5h13.5a2.5 2.5 0 0 0 2.5-2.5v-5.5m-14-9.5v13.5m9.5-13.5v13.5M12 3.75v13.5");
}

</style>
