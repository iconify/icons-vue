<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gs4dm0yep"/><path class="dcaedetha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fake-gps" /></template>
<style>
.dcaedetha {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.898 24.888h6.483m1.466-4.498H2.37c4.82 8.561 2.415 8.809 11.499 8.809l3.218 5.574h2.09m23.925-9.885h-6.483m-1.466-4.498H45.63c-4.82 8.561-2.415 8.809-11.499 8.809l-3.218 5.574h-2.09");
}

.gs4dm0yep {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.935 7.302c-6.191 0-11.21 5.019-11.21 11.21c0 8.778 8.564 19.363 10.799 21.95a.685.685 0 0 0 1.036 0c2.184-2.57 10.585-13.171 10.585-21.95c0-6.191-5.019-11.21-11.21-11.21m0 15.415a4.196 4.196 0 1 1 4.188-4.205v.008a4.19 4.19 0 0 1-4.188 4.188z");
}

</style>
