<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="shvbo-hvj"/><path class="nshajsn3n"/><circle class="dnf72bcoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cakewallet-alt" /></template>
<style>
.dnf72bcoh {
  cx: 27.152px;
  cy: 24px;
  r: 11.35px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nshajsn3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.383 27.58c-1.955-5.95 1.284-12.358 7.234-14.313A11.34 11.34 0 0 1 35.152 16l7.2-7.2a21.47 21.47 0 0 0-15.29-6.3c-11.874.047-21.461 9.711-21.414 21.585s9.71 21.462 21.584 21.415a21.5 21.5 0 0 0 15.04-6.22l-7.12-7.21c-4.449 4.416-11.635 4.389-16.05-.06a11.4 11.4 0 0 1-1.65-2.11");
}

.shvbo-hvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.383 27.58h4.77v-7.74l6 6l6-6v7.74h4.79");
}

</style>
