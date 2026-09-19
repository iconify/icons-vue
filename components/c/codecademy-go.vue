<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ui_10f22s"/><path class="jhxq08bqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:codecademy-go" /></template>
<style>
.jhxq08bqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.92 19.933a7.484 7.484 0 1 0 0 8.135m11.124 8.466H43.5");
}

.ui_10f22s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.466h25.067v25.067H4.5z");
}

</style>
