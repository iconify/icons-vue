<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rj9jyvboq"/><path class="kly-qv4ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bixby" /></template>
<style>
.kly-qv4ia {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.715 22.547a6.865 6.865 0 1 1-6.865 6.865v-6.865Zm-6.865 0V5.57");
}

.rj9jyvboq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5A18.5 18.5 0 1 1 5.5 24V5.5Z");
}

</style>
