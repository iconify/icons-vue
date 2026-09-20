<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh8ry1bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collapse-content-sharp" /></template>
<style>
.wh8ry1bdn {
  fill: currentColor;
  d: path("M11 13v6H9v-4H5v-2zm4-8v4h4v2h-6V5z");
}

</style>
