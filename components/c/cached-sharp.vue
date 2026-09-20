<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slvnfnbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cached-sharp" /></template>
<style>
.slvnfnbux {
  fill: currentColor;
  d: path("M12.05 20q-3.35 0-5.7-2.325T4 12v-.175l-1.6 1.6l-1.4-1.4l4-4l4 4l-1.4 1.4l-1.6-1.6V12q0 2.5 1.763 4.25T12.05 18q.65 0 1.275-.15t1.225-.45l1.5 1.5q-.95.55-1.95.825T12.05 20M19 15.975l-4-4l1.4-1.4l1.6 1.6V12q0-2.5-1.763-4.25T11.95 6q-.65 0-1.275.15T9.45 6.6l-1.5-1.5q.95-.55 1.95-.825T11.95 4q3.35 0 5.7 2.325T20 12v.175l1.6-1.6l1.4 1.4z");
}

</style>
