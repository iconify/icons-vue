<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="imw9lgb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:element-alt" /></template>
<style>
.imw9lgb2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.28 6a2.47 2.47 0 0 1 2.44-2.5a16.4 16.4 0 0 1 16.4 16.4a2.46 2.46 0 0 1-4.92 0A11.44 11.44 0 0 0 20.76 8.46A2.47 2.47 0 0 1 18.28 6m11.44 36a2.46 2.46 0 0 1-2.46 2.46a16.4 16.4 0 0 1-16.4-16.4a2.46 2.46 0 1 1 4.92 0a11.44 11.44 0 0 0 11.44 11.48a2.47 2.47 0 0 1 2.5 2.46M6 29.72a2.47 2.47 0 0 1-2.5-2.44a16.4 16.4 0 0 1 16.4-16.4a2.46 2.46 0 1 1 0 4.92A11.44 11.44 0 0 0 8.46 27.24A2.47 2.47 0 0 1 6 29.72m36-11.44a2.46 2.46 0 0 1 2.46 2.46a16.4 16.4 0 0 1-16.4 16.4a2.46 2.46 0 0 1 0-4.92a11.44 11.44 0 0 0 11.48-11.44a2.47 2.47 0 0 1 2.46-2.5");
}

</style>
