<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihgqvjcoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbc-sport" /></template>
<style>
.ihgqvjcoo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 6.078h37v11.948h-37zm13.029 11.948H42.5v11.948H18.529zm10.603 11.948H42.5v11.948H29.132z");
}

</style>
