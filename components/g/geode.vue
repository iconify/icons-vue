<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hzeeagn7b"/><path class="cyqjnmbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geode" /></template>
<style>
.cyqjnmbaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.8 22.339L24 13.475l12.2 8.864l-4.66 14.342H16.46");
}

.hzeeagn7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.683L3.689 19.44l7.758 23.877h25.106l7.758-23.877");
}

</style>
