<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-3z65btj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:engine-oil" /></template>
<style>
.q-3z65btj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.25 1.75h-.5q-2.5 0-2.5 2.5v.5q0 .564.127 1H8.5q-.149 0-.287.057t-.243.163l-3.5 3.5q-.106.105-.163.243T4.25 10v9q0 2.75 2.75 2.75h10q2.75 0 2.75-2.75V8.5q0-2.75-2.75-2.75h-2.377q.127-.436.127-1v-.5q0-2.5-2.5-2.5m.28 8.72q2.72 2.719 2.72 4.78q0 3.25-3.25 3.25t-3.25-3.25q0-2.061 2.72-4.78q.105-.106.243-.163T12 10.25t.287.057t.243.163");
}

</style>
