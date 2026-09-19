<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pulqawl3f"/><path class="x493s0bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbw-cupid" /></template>
<style>
.pulqawl3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.905 19.664c-6.038-6.608-15.95-16.293-20.45-10.653c-5.289 6.627 12.703 24.268 22.102 31.674");
}

.x493s0bmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.095 19.664c6.038-6.608 15.95-16.293 20.451-10.653c5.288 6.627-12.704 24.268-22.103 31.674");
}

</style>
