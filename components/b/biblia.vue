<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o707_xbjc"/><path class="csak_ob2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:biblia" /></template>
<style>
.csak_ob2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.06 14.444v4.213h-4.213v4.213h4.213v8.676h4.211V22.87h4.213v-4.213H28.27v-4.213Z");
}

.o707_xbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2m4.33-2v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

</style>
