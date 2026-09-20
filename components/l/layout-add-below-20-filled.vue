<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yhspthftk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-add-below-20-filled" /></template>
<style>
.yhspthftk {
  fill: currentColor;
  d: path("M16.5 16a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1zM14 3a3 3 0 0 1 3 3v5.5a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5V6a3 3 0 0 1 3-3z");
}

</style>
