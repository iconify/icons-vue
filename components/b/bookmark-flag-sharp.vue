<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppxkdxb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-flag-sharp" /></template>
<style>
.ppxkdxb4u {
  fill: currentColor;
  d: path("M9.808 13.692h.884v-3h4.193L13.615 9l1.27-1.692H9.808zM6 19.5V4h12v15.5l-6-2.583z");
}

</style>
