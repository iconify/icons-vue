<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e40phdcpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hasheasily" /></template>
<style>
.e40phdcpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("m19.568 4.5l-4.875 39m18.614-39l-4.875 39M9.818 31.09H36.41M11.59 16.023h26.592");
}

</style>
