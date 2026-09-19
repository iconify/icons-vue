<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zaztcersr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aldi-talk-aktivierung" /></template>
<style>
.zaztcersr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.41 24.76l-8.832-1.234l1.916 8.709m3.458-3.737l11.096 10.265M30.41 24.761l11.096 10.265L34.59 42.5L23.494 32.235zm-18.34-.251h5.443m-5.442-4.661H26.2M16.586 5.5v10.09H6.495zm0 0h15.921v17.106m-7.489 15.665H6.494V15.59");
}

</style>
