<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-6gtmmtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-near-me-disabled" /></template>
<style>
.h-6gtmmtu {
  fill: currentColor;
  d: path("M12 6.34L21 3l-3.34 9zm10.61 13.44L4.22 1.39L2.81 2.81l5.07 5.07L3 9.69v1.41l7.07 2.83L12.9 21h1.41l1.81-4.88l5.07 5.07z");
}

</style>
