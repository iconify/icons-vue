<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nb380yijr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:5post" /></template>
<style>
.nb380yijr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 30.9a17.898 17.898 0 0 1-31 0m8.923-3.821c1.483 1.196 2.92 1.743 6.515 1.743h.618c3.325 0 6.02-2.594 6.02-5.795s-2.695-5.795-6.02-5.795h-7.133v-9.08h13.153");
}

</style>
