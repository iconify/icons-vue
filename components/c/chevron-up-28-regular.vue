<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lsy0k9k9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-28-regular" /></template>
<style>
.lsy0k9k9k {
  fill: currentColor;
  d: path("M23.78 18.53a.75.75 0 0 1-1.06 0L14 9.81l-8.72 8.72a.75.75 0 0 1-1.06-1.06l9.25-9.25a.75.75 0 0 1 1.06 0l9.25 9.25a.75.75 0 0 1 0 1.06");
}

</style>
