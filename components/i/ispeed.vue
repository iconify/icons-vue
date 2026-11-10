<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gsdiqtb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ispeed" /></template>
<style>
.gsdiqtb9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 29.469v8.382m7.4-14.392v10.114m7.4-16.426v22.47m7.4-31.235v22.285m7.4-11.788v17.67m7.4-23.366v17.391");
}

</style>
