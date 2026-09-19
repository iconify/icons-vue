<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dun31actk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cloud" /></template>
<style>
.dun31actk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.784 35.573h23.978c13.016 0 10.84-19.586-2.215-15.243c0-10.876-19.586-10.876-19.586 2.178C2.073 20.33 2.073 35.573 10.784 35.573");
}

</style>
