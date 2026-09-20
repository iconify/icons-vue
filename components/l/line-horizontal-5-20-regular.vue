<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dxkkfcbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-5-20-regular" /></template>
<style>
.dxkkfcbbn {
  fill: currentColor;
  d: path("M2 3.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5m0 6a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5M2.5 6a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zM2 12.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5m.5 2.5a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1z");
}

</style>
