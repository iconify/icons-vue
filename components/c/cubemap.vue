<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3beymmwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cubemap" /></template>
<style>
.w3beymmwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 4.75H12V9.5h9.5v4.75H12V19H7.25v-4.75H2.5V9.5h4.75Zm0 4.75H12m-4.75 4.75H12M7.25 9.5v4.75M12 9.5v4.75m4.75-4.75v4.75");
}

</style>
