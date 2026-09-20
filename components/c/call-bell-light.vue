<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="megtafztg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:call-bell-light" /></template>
<style>
.megtafztg {
  fill: currentColor;
  d: path("M24 182h208a6 6 0 0 0 0-12h-10v-18a94.1 94.1 0 0 0-88-93.8V38h18a6 6 0 0 0 0-12h-48a6 6 0 0 0 0 12h18v20.2A94.1 94.1 0 0 0 34 152v18H24a6 6 0 0 0 0 12m22-30a82 82 0 0 1 164 0v18H46Zm192 56a6 6 0 0 1-6 6H24a6 6 0 0 1 0-12h208a6 6 0 0 1 6 6");
}

</style>
