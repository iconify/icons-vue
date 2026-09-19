<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x4n9libbh"/><path class="dpznszjnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hail" /></template>
<style>
.dpznszjnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.332 40.595l19.152-33.35H14.388l18.834 33.422");
}

.x4n9libbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 23.835l10.06 16.92h18.696L43.5 23.847");
}

</style>
