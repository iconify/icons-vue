<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zjzmaebgm"/><path class="k7apubcen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banking4" /></template>
<style>
.k7apubcen {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.579 19.88H39.42a3.07 3.07 0 0 1 3.079 3.067V39.57a3.07 3.07 0 0 1-3.066 3.079H8.58a3.07 3.07 0 0 1-3.08-3.065V22.96a3.07 3.07 0 0 1 3.066-3.08zm33.921-.801v-3.183a3.07 3.07 0 0 0-3.066-3.078H8.58a3.07 3.07 0 0 0-3.08 3.065v3.196m37-7.167V8.65a3 3 0 0 0-3.001-3H8.58A3.07 3.07 0 0 0 5.5 8.715v3.197");
}

.zjzmaebgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.154 36.57l5.305-5.305l-5.305-5.304");
}

</style>
