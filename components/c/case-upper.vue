<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7m4o4wbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-upper" /></template>
<style>
.o7m4o4wbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 18L3.7857 13L6.0583 6.668C6.3743 5.783 7.6257 5.783 7.9417 6.668L10.2143 13L12 18M10.2143 13H3.7857M21.1 15L19.8091 10.697C19.5412 9.805 18.4588 9.805 18.1909 10.697L16.9 15M21.1 15H16.9M21.1 15L22 18M16.9 15L16 18");
}

</style>
