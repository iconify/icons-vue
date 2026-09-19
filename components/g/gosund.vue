<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x_2oo65ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gosund" /></template>
<style>
.x_2oo65ku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 23.41V20.8a5.95 5.95 0 0 0-2.316-4.712L28.076 6.75a6.675 6.675 0 0 0-8.152 0L7.816 16.088A5.95 5.95 0 0 0 5.5 20.799v13.143c0 5.696 3.001 8.697 6.703 8.697h23.594a6.703 6.703 0 0 0 6.703-6.703h0a6.703 6.703 0 0 0-6.703-6.703H28.2");
}

</style>
