<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym3gr-bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-security-update" /></template>
<style>
.ym3gr-bqr {
  fill: currentColor;
  d: path("M5 3v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2m12 15H7V6h10zm-1-6h-3V8h-2v4H8l4 4z");
}

</style>
