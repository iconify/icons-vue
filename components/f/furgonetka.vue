<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lqufc9bvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:furgonetka" /></template>
<style>
.lqufc9bvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.38 34.75v-21.5l13.965-8.062a9.31 9.31 0 0 1 9.31 0L42.62 13.25v21.5L24 45.5l-12.415-7.168M5.382 13.248l12.412 7.168M24 24l18.62-10.748M5.38 24l9.31 5.375");
}

</style>
