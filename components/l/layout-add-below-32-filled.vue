<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wz_y-2buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-below-32-filled" /></template>
<style>
.wz_y-2buq {
  fill: currentColor;
  d: path("M28 27a1 1 0 1 1 0 2H4a1 1 0 1 1 0-2zM24.5 3A4.5 4.5 0 0 1 29 7.5V20a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
