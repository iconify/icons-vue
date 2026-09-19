<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1s45cgre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clozemaster" /></template>
<style>
.m1s45cgre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.86 42.5l.544-36.456h9.25v4.897h4.897v5.441h4.898v-5.44h4.897V5.5h9.794v37h-9.794V26.72h-4.897v4.898H21.55l.011-4.952l-4.363.055V42.5z");
}

</style>
