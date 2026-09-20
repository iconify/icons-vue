<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vdtkey4eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-up-left-32-light" /></template>
<style>
.vdtkey4eh {
  fill: currentColor;
  d: path("M12.854 5.146a.5.5 0 0 1 0 .708L7.707 11H19a7 7 0 1 1 0 14H9.5a.5.5 0 0 1 0-1H19a6 6 0 0 0 0-12H7.707l5.147 5.146a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708l6-6a.5.5 0 0 1 .708 0");
}

</style>
