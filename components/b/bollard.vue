<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="che--w_gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bollard" /></template>
<style>
.che--w_gk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25V12a2 2 0 0 1 4 0v9.25Zm7.25 0V9.5a2 2 0 0 1 4 0v11.75Zm7.25 0V12a2 2 0 0 1 4 0v9.25ZM2.75 15.5h4m3.25-2h4m3.25 2h4");
}

</style>
