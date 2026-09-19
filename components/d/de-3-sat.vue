<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hwn9df2lg"/><path class="phdj3eblz"/><path class="wet5n_boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:de-3-sat" /></template>
<style>
.hwn9df2lg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.43 10.538h15.337L35.805 4.5H8.39z");
}

.phdj3eblz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.803 20.49L35.805 4.5l3.804 3.804l-16.001 15.99z");
}

.wet5n_boy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.5 36.237l5.241-4.432c8.043 11.678 24.953 1.843 12.764-10.403l4.83-4.83c16.4 16.67-5.3 38.493-22.835 19.666Z");
}

</style>
