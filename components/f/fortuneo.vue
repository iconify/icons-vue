<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jv0rn2smi"/><path class="ekxdchyro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fortuneo" /></template>
<style>
.ekxdchyro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.93 43.5l10.21-14.2l-5.95-8.19ZM42 15.57l-11.89 5.37l-1-5.37Zm0 0");
}

.jv0rn2smi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.56 8.58l-2.45-.18l-2.76-3.9l-4.63 3l.49 3.19l-1.74 1.5ZM18.19 21.11L34.48 43.5l-5.41-27.93H6Zm0 0");
}

</style>
