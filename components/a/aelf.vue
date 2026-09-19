<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d4lgrxbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aelf" /></template>
<style>
.d4lgrxbqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.566 43.5l1.166-2.497M18.366 4.5h3.815l13.455 36.492l2.497 1.167M20.86 9.514L11.963 30.92m13.752-8.101l-1.021-2.69l-7.892-.02M9.867 30.92h4.004m6.516-22.735l1.284 3.611m2.695 7.412l1.285 3.611");
}

</style>
