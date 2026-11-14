<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb8te0phb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:field-of-view" /></template>
<style>
.gb8te0phb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.399 4.399Q1.25 7.547 1.25 12t3.149 7.601Q7.547 22.75 12 22.75t7.601-3.149Q22.75 16.453 22.75 12t-3.149-7.601Q16.453 1.25 12 1.25T4.399 4.399");
}

</style>
