<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pb1gm4bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hgem-go" /></template>
<style>
.pb1gm4bjo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.654v10.867a2.906 2.906 0 0 1-2.906 2.907h-4.827c-1.798 0-3.46-.96-4.36-2.517L4.174 26.517a5.03 5.03 0 0 1 0-5.034l9.187-15.91M24 19.345V8.479a2.906 2.906 0 0 1 2.906-2.907h4.827c1.798 0 3.46.96 4.36 2.517l7.732 13.394a5.03 5.03 0 0 1 0 5.034l-9.186 15.91");
}

</style>
