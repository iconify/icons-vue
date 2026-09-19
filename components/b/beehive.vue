<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5ft33bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beehive" /></template>
<style>
.s5ft33bmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.63 24l4.696-8.137h9.397L24.42 24l-4.698 8.137h-9.397zm17.95 10.363l4.695-8.137h9.397l4.698 8.137l-4.698 8.137h-9.397zm0-20.726L28.274 5.5h9.397l4.698 8.137l-4.698 8.137h-9.397z");
}

</style>
