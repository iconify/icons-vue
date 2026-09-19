<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iss36n4zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hagebau" /></template>
<style>
.iss36n4zm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.865 14.247L32.062 5.5h-9.124M6.135 14.247L15.938 5.5h9.124m16.803 28.253L32.062 42.5h-9.124M6.135 33.753l9.803 8.747h9.124M28.97 32v-9.225s.134-1.387-1.546-1.387H19.48M19.027 32V15.825");
}

</style>
