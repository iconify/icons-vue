<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hi1f4bf8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-flow-diagonal-up-right-16-regular" /></template>
<style>
.hi1f4bf8u {
  fill: currentColor;
  d: path("M12.854 3.854a.5.5 0 0 0-.708-.708L5.88 9.414a2.5 2.5 0 1 0 .707.707zM3 11.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0");
}

</style>
