<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uvdbb061o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-clock-face-twelve-thirty" /></template>
<style>
.uvdbb061o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.04 24.067v15.887m.03-16.117l2.661-9.929M2.5 24c-.004 11.87 9.62 21.496 21.493 21.5c11.875.004 21.503-9.616 21.507-21.487V24c.004-11.87-9.62-21.496-21.493-21.5C12.132 2.496 2.504 12.116 2.5 23.987z");
}

</style>
