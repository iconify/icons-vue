<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w08eswbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-left-16-regular" /></template>
<style>
.w08eswbvx {
  fill: currentColor;
  d: path("M7.707 8.5H14.5a.5.5 0 0 0 0-1H7.707l2.147-2.146a.5.5 0 0 0-.708-.708l-3 3a.5.5 0 0 0 0 .708l3 3a.5.5 0 0 0 .708-.708zM1 8a2 2 0 1 1 4 0a2 2 0 0 1-4 0m1 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
