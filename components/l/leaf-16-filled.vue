<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bc-qcobcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:leaf-16-filled" /></template>
<style>
.bc-qcobcc {
  fill: currentColor;
  d: path("M11.275 4.536A4.886 4.886 0 0 1 8.5 13.022V14.5a.5.5 0 1 1-1 0v-1.478a4.886 4.886 0 0 1-2.775-8.486l2.437-2.2a1.25 1.25 0 0 1 1.676 0zM8.5 7.501a.5.5 0 0 0-1 0v4.514a4 4 0 0 0 1 0z");
}

</style>
