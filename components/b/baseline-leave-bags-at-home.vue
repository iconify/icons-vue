<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rde32lblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-leave-bags-at-home" /></template>
<style>
.rde32lblp {
  fill: currentColor;
  d: path("M11.83 9h.92v.92l1.75 1.75V9H16v4.17l3 3V8c0-1.1-.9-2-2-2h-2V3c0-.55-.45-1-1-1h-4c-.55 0-1 .45-1 1v3h-.17zM11 4h2v2h-2zm10.19 17.19L2.81 2.81L1.39 4.22l3.63 3.63c0 .05-.02.1-.02.15v11c0 1.1.9 2 2 2c0 .55.45 1 1 1s1-.45 1-1h6c0 .55.45 1 1 1s1-.45 1-1c.34 0 .65-.09.93-.24l1.85 1.85zM8 18v-7.17l1.5 1.5V18zm3.25 0v-3.92l1.5 1.5V18zm3.25 0v-.67l.67.67z");
}

</style>
