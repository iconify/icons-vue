<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e2wh50b2x"/><path class="z-b9wm1xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keyboard" /></template>
<style>
.e2wh50b2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.14 14.94v4.53h4.53v-4.53Zm6.8 0v4.53h4.53v-4.53Zm6.79 0v4.53h4.54v-4.53Zm6.8 0v4.53h4.53v-4.53Zm6.8 0v4.53h4.53v-4.53ZM8.14 21.73v4.54h4.53v-4.54Zm6.8 0v4.54h4.53v-4.54Zm6.79 0v4.54h4.54v-4.54Zm6.8 0v4.54h4.53v-4.54Zm6.8 0v4.54h4.53v-4.54Zm-27.19 6.8v4.53h4.53v-4.53Zm6.8 0v4.53h18.12v-4.53Zm20.39 0v4.53h4.53v-4.53Z");
}

.z-b9wm1xz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a2 2 0 0 0-2-2h-35a2 2 0 0 0-2 2v23a2 2 0 0 0 2 2h35a2 2 0 0 0 2-2");
}

</style>
