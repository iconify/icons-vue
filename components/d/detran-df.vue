<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eh254zbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:detran-df" /></template>
<style>
.eh254zbxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.3 20.344v-7.4a7.4 7.4 0 1 0-7.4 7.4h22.2a7.4 7.4 0 1 0-7.4-7.4l.034 7.4m-7.468 7.313l.034 7.4a7.4 7.4 0 1 1-7.4-7.4h22.2a7.4 7.4 0 1 1-7.4 7.4v-7.4");
}

</style>
