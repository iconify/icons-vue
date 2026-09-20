<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehkk5bc9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magnification-small-sharp" /></template>
<style>
.ehkk5bc9y {
  fill: currentColor;
  d: path("M5 11h4V7H5zm-3 9V4h20v16z");
}

</style>
