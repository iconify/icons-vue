<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="q7fuy1bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-ascending-28-regular" /></template>
<style>
.q7fuy1bhy {
  fill: currentColor;
  d: path("M6 13a3 3 0 0 1 3 3v6a3 3 0 1 1-6 0v-6a3 3 0 0 1 3-3m8-5a3 3 0 0 1 3 3v11a3 3 0 1 1-6 0V11a3 3 0 0 1 3-3m8-5a3 3 0 0 1 3 3v16a3 3 0 1 1-6 0V6a3 3 0 0 1 3-3M6 14.5A1.5 1.5 0 0 0 4.5 16v6a1.5 1.5 0 0 0 3 0v-6A1.5 1.5 0 0 0 6 14.5m8-5a1.5 1.5 0 0 0-1.5 1.5v11a1.5 1.5 0 0 0 3 0V11A1.5 1.5 0 0 0 14 9.5m8-5A1.5 1.5 0 0 0 20.5 6v16a1.5 1.5 0 0 0 3 0V6A1.5 1.5 0 0 0 22 4.5");
}

</style>
