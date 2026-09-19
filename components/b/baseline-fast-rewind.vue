<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5hi5oq4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-fast-rewind" /></template>
<style>
.g5hi5oq4a {
  fill: currentColor;
  d: path("M11 18V6l-8.5 6zm.5-6l8.5 6V6z");
}

</style>
