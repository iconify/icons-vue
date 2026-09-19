<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ljx1e_sqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:frost-icon-pack" /></template>
<style>
.ljx1e_sqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5L5.38 13.25v21.5L24 45.5l18.62-10.75v-21.5Zm-3.39 10.23h6.78v22.54h-6.78Z");
}

</style>
