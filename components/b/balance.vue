<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iknnv-3qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:balance" /></template>
<style>
.iknnv-3qe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25v17m-4 0h8M5.75 6.5h12.5m-15 7l2.5-7l2.5 7m7.5 0l2.5-7l2.5 7m-18 .75h6a3 3 0 0 1-6 0m12.5 0h6a3 3 0 0 1-6 0");
}

</style>
