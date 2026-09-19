<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l12z-rjcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ahs-parking" /></template>
<style>
.l12z-rjcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 17.833h12.333v12.333H5.5zm24.667 0H42.5v12.333H30.167zM17.833 30.167h12.333V42.5H17.833zm9.334 0l-9.334-9.334V5.5h12.334v24.667z");
}

</style>
