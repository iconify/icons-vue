<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sc9kzl2qf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dropbox" /></template>
<style>
.sc9kzl2qf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.81 19.36l9.69 6.17l-9.75 6.22L24 25.54l-9.75 6.21l-9.75-6.22l9.69-6.17l-9.69-6.17L14.25 7L24 13.19L33.75 7l9.75 6.21zm-.13 0L24 13.2l-9.68 6.16L24 25.53zM14.32 34.81l9.75-6.22l9.75 6.22L24.07 41z");
}

</style>
