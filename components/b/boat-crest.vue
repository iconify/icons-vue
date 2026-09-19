<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xlg69-iui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boat-crest" /></template>
<style>
.xlg69-iui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.015 33.62l9.61-28.12l8.88 22.2zm-6.67 0h33.31l-4.44 8.88h-24.43z");
}

</style>
