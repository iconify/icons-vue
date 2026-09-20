<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xa3gsz01r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:high-definition-light" /></template>
<style>
.xa3gsz01r {
  fill: currentColor;
  d: path("M176 74h-24a6 6 0 0 0-6 6v96a6 6 0 0 0 6 6h24a54 54 0 0 0 0-108m0 96h-18V86h18a42 42 0 0 1 0 84m-62 6v-42H54v42a6 6 0 0 1-12 0V80a6 6 0 0 1 12 0v42h60V80a6 6 0 0 1 12 0v96a6 6 0 0 1-12 0M26 48a6 6 0 0 1 6-6h192a6 6 0 0 1 0 12H32a6 6 0 0 1-6-6m204 160a6 6 0 0 1-6 6H32a6 6 0 0 1 0-12h192a6 6 0 0 1 6 6");
}

</style>
