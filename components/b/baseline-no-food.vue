<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et629ehcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-no-food" /></template>
<style>
.et629ehcr {
  fill: currentColor;
  d: path("M11.35 8.52L11 5h5V1h2v4h5l-1.38 13.79zM1 21v1c0 .55.45 1 1 1h13c.55 0 1-.45 1-1v-1zm20.9.9L2.1 2.1L.69 3.51l5.7 5.7C3.28 9.87 1 11.99 1 15h11.17l2 2H1v2h15v-.17l4.49 4.49z");
}

</style>
