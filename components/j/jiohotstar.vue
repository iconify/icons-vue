<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8ql7obxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jiohotstar" /></template>
<style>
.p8ql7obxf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.834 17.238l3.22-10.01l.936 11.064L42.5 7.462L29.035 22.506L38.109 30l-12.06-2.986l-5.445 13.759l.176-13.232l-10.42 2.635l7.259-6.03L5.5 18.116l12.997 1.288l-3.044-6.147z");
}

</style>
