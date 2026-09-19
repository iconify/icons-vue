<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx3m0ob5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-gpp-good" /></template>
<style>
.bx3m0ob5w {
  fill: currentColor;
  d: path("M12 2L4 5v6.09c0 5.05 3.41 9.76 8 10.91c4.59-1.15 8-5.86 8-10.91V5zm-1.06 13.54L7.4 12l1.41-1.41l2.12 2.12l4.24-4.24l1.41 1.41z");
}

</style>
