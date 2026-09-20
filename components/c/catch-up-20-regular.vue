<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aj95hmb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:catch-up-20-regular" /></template>
<style>
.aj95hmb_h {
  fill: currentColor;
  d: path("M7.453 7.27a.5.5 0 0 1 .909.04l2.35 5.758c.485 1.188 2.142 1.258 2.725.115l1.23-2.411a.5.5 0 0 1 .446-.273h.972a1.5 1.5 0 1 0 0-1h-.973a1.5 1.5 0 0 0-1.336.819l-1.23 2.41a.5.5 0 0 1-.908-.038l-2.35-5.759c-.485-1.188-2.142-1.258-2.725-.115l-1.23 2.41a.5.5 0 0 1-.445.273h-.973a1.5 1.5 0 1 0 0 1h.973a1.5 1.5 0 0 0 1.336-.818z");
}

</style>
