<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqvutybue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chips-sharp" /></template>
<style>
.hqvutybue {
  fill: currentColor;
  d: path("M7.5 12.5h9v-1h-9zM4 20V4h16v16z");
}

</style>
