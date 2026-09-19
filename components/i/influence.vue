<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="adqkwq0fe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:influence" /></template>
<style>
.adqkwq0fe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.043 19.219v9.636m5.919 0v-9.636l6.384 9.636v-9.636M13.154 35.36L5.5 24l8.126-11.675M42.5 28.497l-5.601 12.937l-15.069-1.103m.869-32.581l13.884-1.184l5.838 12.622");
}

</style>
