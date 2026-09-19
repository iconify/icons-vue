<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ks60ujb4k"/><path class="b7h7neq-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dramawave" /></template>
<style>
.b7h7neq-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.482 8.05L20.687 4.81c-4.637-1.392-9.304 2.08-9.304 6.921v24.39c0 4.938 4.76 8.482 9.492 7.064l9.592-2.874a8.63 8.63 0 0 0 6.15-8.263V14.952a7.21 7.21 0 0 0-5.135-6.903Z");
}

.ks60ujb4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.469 23.243l-7.238-4.39a1.143 1.143 0 0 0-1.736.978v8.778c0 .891.974 1.44 1.736.978l7.238-4.39a1.143 1.143 0 0 0 0-1.955Z");
}

</style>
