<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9pg-hrcq"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beboo" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.x9pg-hrcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.763 27.75a5.5 5.5 0 1 1-9.526-5.5a5.5 5.5 0 0 1 9.526 5.5m2.719-11.709l-.732-2.732l-2.732.732m-1.268 6.196l4-6.928M35.763 25.75a5.5 5.5 0 1 0-9.526-5.5a5.5 5.5 0 0 0 9.526 5.5m-7.513 2.013l-5 8.66m4.098-1.098l-5.196-3");
}

</style>
