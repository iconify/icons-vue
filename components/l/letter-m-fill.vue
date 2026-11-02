<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oly0nib0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-m-fill" /></template>
<style>
.oly0nib0u {
  fill: currentColor;
  d: path("M5 4a1 1 0 0 1 1.894-.447L12 13.764l5.106-10.211A.998.998 0 0 1 19 4v16a1 1 0 0 1-2 0V8.236l-4.106 8.211a.998.998 0 0 1-1.788 0L7 8.236V20a1 1 0 0 1-2 0Z");
}

</style>
