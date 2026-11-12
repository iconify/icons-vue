<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mq0unab-n"/><path class="s93rtjb8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:backspace-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mq0unab-n {
  d: path("M3.48981 15.18L4.17061 16.24C5.35117 18.0781 5.94144 18.9971 6.87114 19.4986C7.80085 20 8.91458 20 11.142 20H13.779C17.6544 20 19.5921 20 20.7961 18.8284C22 17.6569 22 15.7712 22 12C22 8.22876 22 6.34315 20.7961 5.17157C19.5921 4 17.6544 4 13.779 4L11.142 4C8.91458 4 7.80085 4 6.87114 4.50143C5.94144 5.00286 5.35117 5.92191 4.17061 7.76001L3.48981 8.82001C2.4966 10.3664 2 11.1396 2 12C2 12.8604 2.4966 13.6336 3.48981 15.18Z");
}

.s93rtjb8w {
  d: path("M15.5 9.50004L13 12M13 12L10.5 14.5M13 12L10.5 9.50002M13 12L15.5 14.5");
}

</style>
