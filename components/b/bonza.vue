<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_mrucc6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bonza" /></template>
<style>
.j_mrucc6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.926 7.382l-9.287 5.362l9.287 5.362l-9.287 5.362l9.287 5.362L43.5 18.106zM13.538 24.74L4.5 29.894l18.574 10.724l9.037-5.154z");
}

</style>
