<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekh4i74va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:intersection" /></template>
<style>
.ekh4i74va {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.75V7.5a1 1 0 0 1-1 1H2.75M15.5 2.75V7.5a1 1 0 0 0 1 1h4.75m-18.5 7H7.5a1 1 0 0 1 1 1v4.75m12.75-5.75H16.5a1 1 0 0 0-1 1v4.75M12 2.75v2.5m0 13.5v2.5M2.75 12h2.5m13.5 0h2.5");
}

</style>
