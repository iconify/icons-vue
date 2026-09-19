<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bu3uy7xkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emby" /></template>
<style>
.bu3uy7xkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.25 3.5L11.12 14.63l1.75 1.75l-9.37 9.37l11.13 11.13l1.75-1.75l9.37 9.37l11.13-11.13l-1.75-1.75l9.37-9.37l-11.13-11.13l-1.75 1.75Zm-3 12.81l6.86 3.84L33 24l-6.85 3.85l-6.86 3.84V16.31Z");
}

</style>
