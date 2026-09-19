<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzx0bdc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:coconala" /></template>
<style>
.hzx0bdc7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.927 35.728V12.379M29.77 6.408L9.455 18.136m6.773 0a6.771 6.771 0 1 0 0 11.728l20.314-11.728a6.771 6.771 0 1 0-10.157-5.864v23.456a6.771 6.771 0 1 0 10.157-5.864zM9.457 29.864l20.221 11.675");
}

</style>
