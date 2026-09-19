<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o7ttk0jji"/><path class="c47fkddru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:denik-n" /></template>
<style>
.c47fkddru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.174 5.502H42.5V42.5H32.37L17.65 27.665");
}

.o7ttk0jji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.826 42.498H5.5V5.5h10.13l14.72 14.835");
}

</style>
