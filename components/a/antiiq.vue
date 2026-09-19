<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="brl8gubkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:antiiq" /></template>
<style>
.brl8gubkk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24.737h4.481l5.925 4.476l4.468-7.447l4.463 17.857l5.956-31.246l4.469 20.82l4.531-4.46H43.5m-20.329-1.641h14.35");
}

</style>
