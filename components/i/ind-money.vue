<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4f_vyjwg"/><path class="h7iu_pbpp"/><path class="la3o1kijh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ind-money" /></template>
<style>
.h7iu_pbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.767 30.112V18.929l7.409 11.183V11.888m2.915 18.224V18.93h2.516a4.893 4.893 0 0 1 4.893 4.893v1.398a4.893 4.893 0 0 1-4.893 4.892z");
}

.j4f_vyjwg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4m4-23.571v11.183");
}

.la3o1kijh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.299 16.01l-4.123-4.122l-4.123 4.122");
}

</style>
