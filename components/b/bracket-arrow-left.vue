<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiwjijb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-left" /></template>
<style>
.xiwjijb7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.8907 4H18C20.2091 4 22 5.79086 22 8V16C22 18.2091 20.2091 20 18 20H12.8907M2.76928 12H12.8907M7.83 6.5L2.16411 11.6314C1.9453 11.8296 1.9453 12.1704 2.16411 12.3686L7.83 17.5");
}

</style>
