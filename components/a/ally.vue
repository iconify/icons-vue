<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w4nvobbtg"/><path class="mnwi_p2um"/><path class="r1tryf-4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ally" /></template>
<style>
.mnwi_p2um {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.856 32.37a7.68 7.68 0 0 1-6.97-8.074a7.61 7.61 0 0 1 7.333-7.695a7.61 7.61 0 0 1 7.334 7.694");
}

.r1tryf-4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 23.689v18.756H31.537V24.026m-9.299 18.759l8.31-10.416h-6.7");
}

.w4nvobbtg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.144 42.83A18.764 18.764 0 0 1 5.532 22.94a18.656 18.656 0 0 1 18.78-17.767a18.687 18.687 0 0 1 18.18 18.407");
}

</style>
