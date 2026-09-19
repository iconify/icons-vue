<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y_gxu5bhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:armsx2" /></template>
<style>
.y_gxu5bhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.736 9.461L24 3.5l10.264 5.961M24 15.422l-10.264-5.96v29.077M24 44.5V15.423L34.264 9.46v29.08");
}

</style>
