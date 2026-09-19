<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wscgdub1g"/><path class="b4w7efbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:founder-securities" /></template>
<style>
.b4w7efbxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22 5.5L5.5 22v20.5H26L42.5 26V5.5z");
}

.wscgdub1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.75 13.75h20.5v20.5h-20.5z");
}

</style>
