<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls4o5rx5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-to-line" /></template>
<style>
.ls4o5rx5k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 12L17.0587 12M11.1229 5L17.8261 11.5875C18.058 11.8153 18.058 12.1847 17.8261 12.4125L11.1229 19M22 5L22 19");
}

</style>
