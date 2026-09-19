<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p0bcuccct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forkclient" /></template>
<style>
.p0bcuccct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.22 17.78l7.06-7.06M25 12.56l7.07-7.06M35.44 23l7.06-7.07M35.44 23A7.38 7.38 0 0 1 25 12.56M5.5 42.5L25 23");
}

</style>
