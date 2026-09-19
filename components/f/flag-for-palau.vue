<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="re44mpbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-palau" /></template>
<style>
.re44mpbjz {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m-7.867 45.733C15.446 47.733 8.4 40.687 8.4 32s7.046-15.733 15.732-15.733c8.688 0 15.734 7.047 15.734 15.733S32.82 47.733 24.133 47.733");
}

</style>
