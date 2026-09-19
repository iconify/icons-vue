<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="magje54hb"/><path class="x6sd1bb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:get-health" /></template>
<style>
.magje54hb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.61 17.21h-2.778c-1.912 0-2.781.777-3.574 2.238L13.171 41.723");
}

.x6sd1bb3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.875 6.277H22.231c-3.542 0-6.072 1.122-7.998 4.779l-9.666 18.36h25.52c1.388 0 3.023-.74 3.67-1.968l4.139-7.862c.701-1.333.077-2.377-.974-2.377h-3.257m9.766.084l-.792 1.449l-12.572 22.981");
}

</style>
