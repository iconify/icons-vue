<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eig_92_4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kink" /></template>
<style>
.eig_92_4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.257 6.044v13.872L20.826 6.59H5.5l12.515 17.683L5.5 41.956h15.326l9.431-13.327v13.327H42.5V6.044z");
}

</style>
