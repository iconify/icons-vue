<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1cho7bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dhcp" /></template>
<style>
.u1cho7bpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM12 10v6m-7.25 0v-2.5h14.5V16M2.5 16H7v4.5H2.5Zm7.25 0h4.5v4.5h-4.5ZM17 16h4.5v4.5H17Z");
}

</style>
