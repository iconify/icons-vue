<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p2_o1v6gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adaptivebrightnesstile" /></template>
<style>
.p2_o1v6gb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.9 24.87H27m1.56 4.67L24 15.69l-4.66 13.85M24 6l5.54 5.54h6.92v6.92L42 24l-5.54 5.54v6.92h-6.92L24 42l-5.54-5.54h-6.92v-6.92L6 24l5.54-5.54v-6.92h6.92Z");
}

</style>
