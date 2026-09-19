<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="luu10kq5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arenapro" /></template>
<style>
.luu10kq5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 26.957h37M13.759 42.405l-8.256-4.767V16.276L24 5.595l18.498 10.68v21.363l-8.256 4.767");
}

</style>
