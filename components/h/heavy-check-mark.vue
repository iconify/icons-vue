<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ikmse57kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:heavy-check-mark" /></template>
<style>
.ikmse57kr {
  fill: currentColor;
  d: path("M56 2L18.8 42.909L8 34.729H2L18.8 62L62 2z");
}

</style>
