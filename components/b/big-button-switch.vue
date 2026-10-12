<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n15j3qbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:big-button-switch" /></template>
<style>
.n15j3qbuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 15.25h.75a6.5 6.5 0 0 1 13 0h.75a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2m.75 0h13M12 2.75V6.5m-2-2l2 2l2-2");
}

</style>
