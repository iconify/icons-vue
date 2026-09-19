<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zkuiu2b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-egg" /></template>
<style>
.zkuiu2b9k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.5c8.495 0 13.848-7.914 13.848-17.282C37.848 15.537 32.288 5.5 24 5.5S10.152 15.537 10.152 25.218C10.152 34.587 15.505 42.5 24 42.5");
}

</style>
