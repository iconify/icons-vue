<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ict79tqua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cats-are-liquid" /></template>
<style>
.ict79tqua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.63 23.36l10.057-10.056l7.1 8.446m21.843 1.61L33.576 13.304l-7.1 8.446M4.9 30.827s4.32 5.689 8.377 6.443c4.46.83 6.418-3.866 10.954-3.866s6.495 4.696 10.955 3.866c4.058-.754 8.377-6.443 8.377-6.443");
}

</style>
