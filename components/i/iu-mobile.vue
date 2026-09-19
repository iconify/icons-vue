<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vgisl6h9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iu-mobile" /></template>
<style>
.vgisl6h9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.15 43.5h11.7m-11.7-39h11.7M24 4.5v39M11.325 11.813v12.024C11.325 31.15 17.175 37 24 37s12.675-5.85 12.675-13.163V11.813m-3.9-.271h7.8m-33.15 0h7.8");
}

</style>
