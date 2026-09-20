<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kb5o6cbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lifecounter" /></template>
<style>
.kb5o6cbak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.084 38.461a4.694 4.694 0 1 1-9.387 0a4.694 4.694 0 1 1 9.387 0m-18.783 0a4.694 4.694 0 1 1-9.387 0a4.694 4.694 0 0 1 9.387 0m9.392-28.922a4.694 4.694 0 1 1-9.387 0a4.694 4.694 0 1 1 9.387 0M44 20.551a4.694 4.694 0 1 1-9.387 0a4.694 4.694 0 1 1 9.387 0m-30.613 0a4.694 4.694 0 1 1-9.387 0a4.694 4.694 0 0 1 9.387 0");
}

</style>
