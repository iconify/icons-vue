<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hk5u8r19h"/><path class="labfhrppy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:djezzy" /></template>
<style>
.hk5u8r19h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.242 4.711A1.558 1.558 0 0 0 7.906 6.06v35.88a1.558 1.558 0 0 0 2.336 1.349l31.073-17.94a1.558 1.558 0 0 0 0-2.698Z");
}

.labfhrppy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.694 30.5v-13h2.925a5.687 5.687 0 0 1 5.687 5.688v1.625A5.687 5.687 0 0 1 19.62 30.5Z");
}

</style>
