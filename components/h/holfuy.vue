<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="efmt7k5qg"/><path class="dxot2j8uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:holfuy" /></template>
<style>
.dxot2j8uu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.052 42.69l-15.98-27.37L8.26 42.56l15.991-8.17l7.79 4.112");
}

.efmt7k5qg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.25 34.79a19.5 19.5 0 1 1 30.634 3.713");
}

</style>
