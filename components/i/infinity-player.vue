<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_9ge2b8e"/><path class="vrupswb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:infinity-player" /></template>
<style>
.i_9ge2b8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.761 21.504l-1.15-2.1c-2.054-3.751-6.332-5.938-10.494-4.951a9.77 9.77 0 0 0-4.764 2.708c-3.633 3.736-3.633 9.942 0 13.678a9.77 9.77 0 0 0 4.764 2.708c4.162.987 8.44-1.2 10.494-4.951l5.034-9.192c2.054-3.751 6.332-5.938 10.494-4.951a9.77 9.77 0 0 1 4.764 2.708c3.633 3.736 3.633 9.942 0 13.678a10 10 0 0 1-.7.654c-4.615 3.912-11.753 2.225-14.66-3.082l-1.048-1.915");
}

.vrupswb1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.289 24l-6.267-3.875v7.75z");
}

</style>
