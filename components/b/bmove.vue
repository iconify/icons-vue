<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a0ij64b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bmove" /></template>
<style>
.a0ij64b-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.524 42.95l9.931-19.481q-9.644-2.027-9.067-5.787q.34-4.97 14.374-4.341l-2.315 4.919l11.96-5.691l-5.402-7.619l-2.316 4.725q-11.765-.628-17.359 2.412a15.2 15.2 0 0 0-3.859 2.988q-2.77 2.952-1.928 8.007Q9.94 33.74 14.524 42.95");
}

</style>
