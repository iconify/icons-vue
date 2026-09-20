<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="exytv1xbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-left-48-filled" /></template>
<style>
.exytv1xbl {
  fill: currentColor;
  d: path("M25.5 6a1.5 1.5 0 0 1 0 3H11.121l30.44 30.44a1.5 1.5 0 0 1-2.122 2.12L9 11.122V25.5a1.5 1.5 0 0 1-3 0v-18A1.5 1.5 0 0 1 7.5 6z");
}

</style>
