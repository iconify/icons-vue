<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1_6y4d5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sync-fill" /></template>
<style>
.f1_6y4d5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.8582 3.7232C14.0085 3.262 13.0348 3 12 3C8.6863 3 6 5.6863 6 9C3.7909 9 2 10.7909 2 13C2 15.2091 3.7909 17 6 17H7.1186M21.9164 14.5449C21.972 14.8603 22 15.1798 22 15.5C22 18.5376 19.5376 21 16.5 21C13.4624 21 11 18.5376 11 15.5C11 12.4624 13.4624 10 16.5 10C16.8202 10 17.1397 10.028 17.4551 10.0836M15.7343 7.6261L17.4551 10.0836L14.9976 11.8043");
}

</style>
