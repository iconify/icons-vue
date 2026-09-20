<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nbths4b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-in-left-12-filled" /></template>
<style>
.nbths4b4h {
  fill: currentColor;
  d: path("M11 6a.5.5 0 0 0-.5-.5H6.707l1.147-1.146a.5.5 0 1 0-.708-.708l-2 2a.5.5 0 0 0 0 .708l2 2a.5.5 0 1 0 .708-.708L6.707 6.5H10.5A.5.5 0 0 0 11 6M1 6a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0");
}

</style>
