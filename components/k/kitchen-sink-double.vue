<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcf6pkbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kitchen-sink-double" /></template>
<style>
.tcf6pkbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19m-17 0v4.5a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2V13m3 0v4.5a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2V13M12 13V7a2.5 2.5 0 0 1 5 0v1.5");
}

</style>
