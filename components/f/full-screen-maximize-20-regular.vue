<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oley_4b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:full-screen-maximize-20-regular" /></template>
<style>
.oley_4b7c {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2-2h2a.5.5 0 0 1 0 1H5a1 1 0 0 0-1 1v2a.5.5 0 0 1-1 0zm9.5-1.5A.5.5 0 0 1 13 3h2a2 2 0 0 1 2 2v2a.5.5 0 0 1-1 0V5a1 1 0 0 0-1-1h-2a.5.5 0 0 1-.5-.5m-9 9a.5.5 0 0 1 .5.5v2a1 1 0 0 0 1 1h2a.5.5 0 0 1 0 1H5a2 2 0 0 1-2-2v-2a.5.5 0 0 1 .5-.5m13 0a.5.5 0 0 1 .5.5v2a2 2 0 0 1-2 2h-2a.5.5 0 0 1 0-1h2a1 1 0 0 0 1-1v-2a.5.5 0 0 1 .5-.5");
}

</style>
