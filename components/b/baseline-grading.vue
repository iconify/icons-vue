<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfy9l7b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-grading" /></template>
<style>
.rfy9l7b0f {
  fill: currentColor;
  d: path("M4 7h16v2H4zm0 6h16v-2H4zm0 4h7v-2H4zm0 4h7v-2H4zm11.41-2.83L14 16.75l-1.41 1.41L15.41 21L20 16.42L18.58 15zM4 3v2h16V3z");
}

</style>
