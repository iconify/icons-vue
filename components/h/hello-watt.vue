<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d2rcdzbvq"/><path class="w99afpb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hello-watt" /></template>
<style>
.d2rcdzbvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.808 26.692c-5.077-5.076-5.077-13.308 0-18.385c5.076-5.076 13.308-5.076 18.385 0c4.839 4.84 5.065 12.544.68 17.652c-.36.42-.82 1.159-.992 1.684l-.59 1.801a4.14 4.14 0 0 1-3.933 2.851H16.642l12.881 5.603H18.476L27.69 43.5");
}

.w99afpb8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11a6.5 6.5 0 0 1 6.5 6.5");
}

</style>
