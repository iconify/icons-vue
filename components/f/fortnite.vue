<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j_oj9uecm"/><path class="kabd0hl4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fortnite" /></template>
<style>
.j_oj9uecm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.797 41.478V6.522H30.91l-.644 7.67h-5.973v5.739h5.095v7.377H24.41v12.766zm0-3.366L4.5 39.839l1.113-21.9l-.996-9.485h12.18");
}

.kabd0hl4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.748 8.454h12.693l-1.112 8.541L43.5 38.024L24.41 36.92");
}

</style>
