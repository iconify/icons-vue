<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="cisgj5drz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-sound-wave-12-regular" /></template>
<style>
.cisgj5drz {
  fill: currentColor;
  d: path("M6 1a5 5 0 0 1 5 5v3a2 2 0 0 1-2 2h-.5a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 .5-.5H10a4 4 0 1 0-8 0h1.5a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-.5.5H3a2 2 0 0 1-2-2V6a5 5 0 0 1 5-5m0 4a.5.5 0 0 1 .5.5v5a.5.5 0 0 1-1 0v-5A.5.5 0 0 1 6 5M2 9a1 1 0 0 0 1 1V7H2zm7 1a1 1 0 0 0 1-1V7H9z");
}

</style>
