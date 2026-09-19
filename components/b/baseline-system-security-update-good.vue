<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh8ysccrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-system-security-update-good" /></template>
<style>
.rh8ysccrn {
  fill: currentColor;
  d: path("M17 1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 17H7V6h10zm-1-7.95l-1.41-1.41l-3.54 3.54l-1.41-1.41l-1.41 1.41L11.05 15z");
}

</style>
