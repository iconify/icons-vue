<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lwfrorbrl"/><path class="a1gd2d18g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-indonesia" /></template>
<style>
.a1gd2d18g {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M31.8 2c-16.6 0-30 13.4-30 30h60c0-16.6-13.4-30-30-30");
}

.lwfrorbrl {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M31.8 62c16.6 0 30-13.4 30-30h-60c0 16.6 13.4 30 30 30");
}

</style>
