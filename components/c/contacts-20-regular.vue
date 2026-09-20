<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="vitbs1cej"/><path class="sg0vr2bmg"/><path class="wz0jnun2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contacts-20-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sg0vr2bmg {
  d: path("M7 10.75V11a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-.25a.75.75 0 0 0-.75-.75h-4.5a.75.75 0 0 0-.75.75z");
  fill: currentColor;
}

.vitbs1cej {
  d: path("M11.5 7.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0z");
  fill: currentColor;
}

.wz0jnun2y {
  d: path("M4 4v12a2 2 0 0 0 2 2h9.5a.5.5 0 0 0 0-1H6a1 1 0 0 1-1-1h10a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2zm10-1a1 1 0 0 1 1 1v11H5V4a1 1 0 0 1 1-1h8z");
  fill: currentColor;
}

</style>
