<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bczq3c8be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-drop-up-sharp" /></template>
<style>
.bczq3c8be {
  fill: currentColor;
  d: path("M8.192 13.5L12 9.692l3.808 3.808z");
}

</style>
