<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lynbc737v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:grit" /></template>
<style>
.lynbc737v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 31.374l5.281 5.235l9.145-9.38m5.342 6.263H42.5m-37-17.955l5.281 5.234l9.145-9.38m5.342 6.264H42.5");
}

</style>
