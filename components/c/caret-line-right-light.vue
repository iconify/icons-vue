<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xix0kz1qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-right-light" /></template>
<style>
.xix0kz1qr {
  fill: currentColor;
  d: path("M148.24 123.76a6 6 0 0 1 0 8.48l-80 80a6 6 0 0 1-8.48-8.48L135.51 128L59.76 52.24a6 6 0 0 1 8.48-8.48ZM184 42a6 6 0 0 0-6 6v160a6 6 0 0 0 12 0V48a6 6 0 0 0-6-6");
}

</style>
