<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofv50pbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloakroom-hanger" /></template>
<style>
.ofv50pbxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 11l-9 7q-1 1 .5 1h17q1.5 0 .5-1ZM9.75 7A2.25 2.25 0 1 1 12 9.25V11");
}

</style>
