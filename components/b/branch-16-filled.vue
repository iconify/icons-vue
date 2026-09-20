<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l03xnnf0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-16-filled" /></template>
<style>
.l03xnnf0d {
  fill: currentColor;
  d: path("M13.753 7.432a2.5 2.5 0 0 0-2.261-1.43a2.5 2.5 0 0 0-2.446 1.985C7.164 7.86 5.458 6.963 5.073 5.931a2.499 2.499 0 1 0-1.08.02v4.1a2.504 2.504 0 0 0-1.988 2.701a2.499 2.499 0 1 0 4.502-1.733a2.5 2.5 0 0 0-1.514-.968V7.468a7 7 0 0 0 4.048 1.52a2.49 2.49 0 0 0 1.844 1.94a2.498 2.498 0 0 0 3.09-2.12a2.5 2.5 0 0 0-.221-1.375z");
}

</style>
