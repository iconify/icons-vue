<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9665u4uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chase" /></template>
<style>
.q9665u4uc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 30.82l10.27 11.07a1.9 1.9 0 0 0 1.39.61h13.66V30.82ZM17.18 5.5L6.11 15.77a1.9 1.9 0 0 0-.61 1.39v13.66h11.68ZM42.5 17.18L32.23 6.11a1.9 1.9 0 0 0-1.39-.61H17.18v11.68ZM30.82 42.5l11.07-10.27a1.9 1.9 0 0 0 .61-1.39V17.18H30.82Z");
}

</style>
