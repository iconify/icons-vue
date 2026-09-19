<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vc1tzcyyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apivia" /></template>
<style>
.vc1tzcyyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.793 40.03h5.56l-11.55-22.578h-1.605L11.648 40.03h5.559l1.862-3.638h9.862zm-9.474-8.037L24 26.753l2.68 5.24zM5.5 17.321c6.62-5.829 19.877-10.653 30.082-.448H42.5c-6.943-9.794-26.633-13.958-37 .448");
}

</style>
