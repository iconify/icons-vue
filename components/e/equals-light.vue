<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="t4lxztbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:equals-light" /></template>
<style>
.t4lxztbub {
  fill: currentColor;
  d: path("M222 160a6 6 0 0 1-6 6H40a6 6 0 0 1 0-12h176a6 6 0 0 1 6 6M40 102h176a6 6 0 0 0 0-12H40a6 6 0 0 0 0 12");
}

</style>
