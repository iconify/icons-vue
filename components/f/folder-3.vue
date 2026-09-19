<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><path class="b_0cqgbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:folder-3" /></template>
<style>
.b_0cqgbop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.109 32.069c.972.81 1.783 1.135 4.053 1.135h.486a3.25 3.25 0 0 0 3.243-3.243h0a3.25 3.25 0 0 0-3.243-3.242m-4.54-5.512c.973-.811 1.946-1.135 4.054-1.135h.486a3.25 3.25 0 0 1 3.243 3.242h0a3.25 3.25 0 0 1-3.243 3.243m-2.432.162h2.432");
}

.h0qgeuwow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

</style>
