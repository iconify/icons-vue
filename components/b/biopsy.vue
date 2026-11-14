<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzodb_bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:biopsy" /></template>
<style>
.gzodb_bif {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m21.608 6.281l-3.889-3.889v-.001q-1.414-1.412-2.828.001q-1.412 1.413.001 2.827l1.534 1.535q-.129.012-.247.068t-.209.148l-9.25 9.25q-.11.11-.168.254q-.176.09-.332.246q-.244.243-.325.537q-.12.017-.23.072q-.109.054-.195.141l-2.5 2.5q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l2.401-2.4q.082.049.175.089l.225.096q.703.3 1.243-.241t.241-1.243l-.097-.226q-.039-.093-.088-.174l8.9-8.901q.092-.092.148-.209q.056-.118.068-.247l1.535 1.535q1.414 1.412 2.828-.001q1.412-1.414-.001-2.827");
}

</style>
