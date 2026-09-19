<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w9-uublqs"/><path class="dtpchibou"/><path class="cak1wkb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duo" /></template>
<style>
.cak1wkb1i {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("m30.4 24.9l4.6 4.7V18.4L30.4 23Z");
}

.dtpchibou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.5 17.1h11.3a2.65 2.65 0 0 1 2.6 2.6v8.7a2.65 2.65 0 0 1-2.6 2.6H16.5a2.65 2.65 0 0 1-2.6-2.6v-8.7a2.65 2.65 0 0 1 2.6-2.6");
}

.w9-uublqs {
  fill: none;
  stroke: currentColor;
  d: path("M24 5.5A18.5 18.5 0 1 0 42.5 24V8c0-1.8-.8-2.5-2.5-2.5Z");
}

</style>
