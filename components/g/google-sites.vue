<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="om-iyx24n"/><path class="dbdqx99oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-sites" /></template>
<style>
.dbdqx99oc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.375 30.036h.929a3.02 3.02 0 0 1 3.018 3.018h0a3.02 3.02 0 0 1-3.018 3.017h-.929a3.02 3.02 0 0 1-3.018-3.017h0a3.02 3.02 0 0 1 3.018-3.018M11.304 40.25a5.804 5.804 0 0 0 5.803-5.804V17.964H5.5m39 0H17.107");
}

.om-iyx24n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.683c0-2.7 0-4.049.424-5.12a6.04 6.04 0 0 1 3.39-3.39c1.07-.423 2.42-.423 5.119-.423h21.134c2.7 0 4.049 0 5.12.424a6.04 6.04 0 0 1 3.39 3.39c.423 1.07.423 2.42.423 5.119v14.634c0 2.7 0 4.049-.424 5.12a6.04 6.04 0 0 1-3.39 3.39c-1.07.423-2.42.423-5.119.423H14.433c-2.699 0-4.049 0-5.12-.424a6.04 6.04 0 0 1-3.39-3.39c-.423-1.07-.423-2.42-.423-5.119z");
}

</style>
