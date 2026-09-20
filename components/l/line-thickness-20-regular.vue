<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t30w2-bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-thickness-20-regular" /></template>
<style>
.t30w2-bwc {
  fill: currentColor;
  d: path("M2 4.5a.5.5 0 0 1 .5-.5h15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1-.5-.5m0 10A1.5 1.5 0 0 1 3.5 13h13a1.5 1.5 0 0 1 0 3h-13A1.5 1.5 0 0 1 2 14.5M3 8a1 1 0 0 0 0 2h14a1 1 0 1 0 0-2z");
}

</style>
