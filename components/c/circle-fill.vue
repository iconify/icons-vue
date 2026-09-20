<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v4in35ekt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:circle-fill" /></template>
<style>
.v4in35ekt {
  fill: currentColor;
  d: path("M232 128A104 104 0 1 1 128 24a104.13 104.13 0 0 1 104 104");
}

</style>
