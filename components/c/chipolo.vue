<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kq-53ccdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chipolo" /></template>
<style>
.kq-53ccdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 32.075a3.865 3.865 0 1 1-7.73 0a3.865 3.865 0 1 1 7.73 0m-15.96-3.676a11.94 11.94 0 0 1-11.1 7.54C9.846 35.94 4.5 30.594 4.5 24s5.346-11.94 11.94-11.94a11.94 11.94 0 0 1 11.099 7.541");
}

</style>
