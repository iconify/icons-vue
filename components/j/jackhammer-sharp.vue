<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pynpim_1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jackhammer-sharp" /></template>
<style>
.pynpim_1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5h18.5M12 4.5v3m-3.25 0h6.5V15h-6.5zm0 3h6.5M12 15v5.5m-6-1l-2 1.75m14-1.75l2 1.75m-13.5-4.5H4m13.5 0H20");
}

</style>
