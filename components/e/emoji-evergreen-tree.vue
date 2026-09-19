<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qdd4m2bsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-evergreen-tree" /></template>
<style>
.qdd4m2bsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 34.866l12.23.78l-5.793-10.853l3.405.55l-5.327-8.99l3.176.222L24.001 5.5l-7.365 11.314l2.849-.461l-5.557 8.99l3.635-.55l-5.792 10.852zm0 0V42.5");
}

</style>
