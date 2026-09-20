<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="msr6rlbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-32-regular" /></template>
<style>
.msr6rlbnw {
  fill: currentColor;
  d: path("M12.817 2.318a4.5 4.5 0 0 1 6.364 0L29.68 12.817a4.5 4.5 0 0 1 0 6.364L19.181 29.68a4.5 4.5 0 0 1-6.364 0l-10.5-10.499a4.5 4.5 0 0 1 0-6.364zm4.949 1.414a2.5 2.5 0 0 0-3.535 0L3.73 14.23a2.5 2.5 0 0 0 0 3.535l10.5 10.499a2.5 2.5 0 0 0 3.535 0l10.499-10.5a2.5 2.5 0 0 0 0-3.534z");
}

</style>
