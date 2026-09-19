<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u_vbuwu7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apobank" /></template>
<style>
.u_vbuwu7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24c0-10.217-8.283-18.5-18.5-18.5S5.5 13.783 5.5 24S13.783 42.5 24 42.5a18.5 18.5 0 0 0 4.632-.59l.004-9.906A9.25 9.25 0 1 1 33.25 24v18.5h9.25z");
}

</style>
