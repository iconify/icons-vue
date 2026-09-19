<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sykfadwpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lanxchange" /></template>
<style>
.sykfadwpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24L5.5 5.5s8.75 17.633 9.25 18.5c-.5.868-9.25 18.5-9.25 18.5zl18.5 18.5S33.75 24.868 33.25 24c.499-.864 9.25-18.5 9.25-18.5Z");
}

</style>
