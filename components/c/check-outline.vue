<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4osr_8qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:check-outline" /></template>
<style>
.l4osr_8qb {
  fill: currentColor;
  d: path("M18.4697 6.46973C18.7626 6.17684 19.2373 6.17684 19.5302 6.46973C19.8231 6.76262 19.8231 7.23738 19.5302 7.53028L9.53022 17.5303C9.23732 17.8232 8.76256 17.8232 8.46967 17.5303L4.46967 13.5303C4.17678 13.2374 4.17678 12.7626 4.46967 12.4697C4.76256 12.1768 5.23732 12.1768 5.53022 12.4697L8.99994 15.9395L18.4697 6.46973Z");
}

</style>
