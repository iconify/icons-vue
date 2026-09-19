<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="edc_91b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audioteka" /></template>
<style>
.edc_91b3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.991 20.501L11.009 5.5v30.001zm-25.982 18.5L36.991 24M11.009 42.5l25.982-15.001");
}

</style>
