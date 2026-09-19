<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x_h4xtb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hidden-settings" /></template>
<style>
.x_h4xtb7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.54 38.25l5.11-2.06a15.7 15.7 0 0 0 3.46 2l.77 5.43a1 1 0 0 0 1 .86h8.2a1 1 0 0 0 1-.86l.77-5.43a15.4 15.4 0 0 0 3.46-2l5.11 2.06a1 1 0 0 0 1.25-.44l4.1-7.11a1 1 0 0 0-.25-1.31L39.23 26a17 17 0 0 0 .14-2a17 17 0 0 0-.14-2l4.33-3.39m-5.1-8.86l-5.11 2.06a15.7 15.7 0 0 0-3.46-2l-.77-5.43a1 1 0 0 0-1-.86H19.9a1 1 0 0 0-1 .86l-.77 5.43a15.4 15.4 0 0 0-3.46 2L9.54 9.75a1 1 0 0 0-1.25.44l-4.1 7.11a1 1 0 0 0 .25 1.31L8.76 22a17 17 0 0 0-.14 2a17 17 0 0 0 .14 2l-4.32 3.39M24 31.18a7.18 7.18 0 1 1 7.17-7.19V24a7.17 7.17 0 0 1-7.16 7.18Z");
}

</style>
