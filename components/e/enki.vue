<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c6fpw15de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:enki" /></template>
<style>
.c6fpw15de {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.337 21.878L4.5 25.592l5.837 3.714m27.326-7.428l5.837 3.714l-5.837 3.714m-8.224 3.184l5.837-16.98M24.728 29.07a4.96 4.96 0 0 1-9.27-2.457v-3.225a4.96 4.96 0 1 1 9.92 0V25h-9.92");
}

</style>
