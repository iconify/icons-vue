<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t-m64h6xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:currency-dollar-simple-thin" /></template>
<style>
.t-m64h6xo {
  fill: currentColor;
  d: path("M196 168a44.05 44.05 0 0 1-44 44h-20v20a4 4 0 0 1-8 0v-20h-20a44.05 44.05 0 0 1-44-44a4 4 0 0 1 8 0a36 36 0 0 0 36 36h48a36 36 0 0 0 0-72h-40a44 44 0 0 1 0-88h12V24a4 4 0 0 1 8 0v20h12a44.05 44.05 0 0 1 44 44a4 4 0 0 1-8 0a36 36 0 0 0-36-36h-32a36 36 0 0 0 0 72h40a44.05 44.05 0 0 1 44 44");
}

</style>
