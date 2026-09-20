<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eircgdc5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fast-memo" /></template>
<style>
.eircgdc5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.878 6.5l-.662 2.47a3.07 3.07 0 0 0 2.965 3.863h19.122a5.865 5.865 0 0 0 5.665-4.346L42.5 6.5zM10.32 23.513L5.5 41.5h9.208l4.287-16H33.41a5.21 5.21 0 0 0 5.035-3.864l.662-2.47H15.985a5.865 5.865 0 0 0-5.665 4.348");
}

</style>
