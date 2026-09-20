<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l54-o1bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-up-20-filled" /></template>
<style>
.l54-o1bxz {
  fill: currentColor;
  d: path("M6.28 2.97a.75.75 0 0 0-1.06 1.06l4.25 4.25a.75.75 0 0 0 1.06 0l4.25-4.25a.75.75 0 0 0-1.06-1.06L10 6.69zm8.5 13l-4.25-4.25a.75.75 0 0 0-1.06 0l-4.25 4.25a.75.75 0 1 0 1.06 1.06L10 13.31l3.72 3.72a.75.75 0 1 0 1.06-1.06");
}

</style>
