<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfrlw2b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:american-football" /></template>
<style>
.tfrlw2b7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V13.5m-7.25 0h14.5m-14.5 0V3.25m14.5 10.25V3.25M9.13 9.01a3.6 2.1-40 1 1 5.74-4.02a3.6 2.1-40 1 1-5.74 4.02");
}

</style>
