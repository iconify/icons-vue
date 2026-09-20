<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oxu3sdsur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-right-32-regular" /></template>
<style>
.oxu3sdsur {
  fill: currentColor;
  d: path("M11.293 26.707a1 1 0 0 1 0-1.414L20.586 16l-9.293-9.293a1 1 0 0 1 1.414-1.414l10 10a1 1 0 0 1 0 1.414l-10 10a1 1 0 0 1-1.414 0");
}

</style>
