<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="inkgmu70s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cartola" /></template>
<style>
.inkgmu70s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.742 31.657l.556-5.225l1.778-16.584H11.119l1.751 17.168l.475 4.641m22.626 6.495l-27.846-1.69L5.5 31.661h37zm-1.673-11.72l-21.428.584");
}

</style>
