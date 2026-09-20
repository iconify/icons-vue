<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mi-08xbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bidirectional-left-right-28-filled" /></template>
<style>
.mi-08xbjt {
  fill: currentColor;
  d: path("M10.707 7.295a1 1 0 0 1 0 1.414l-4.293 4.293h15.172l-4.293-4.293a1 1 0 0 1 1.414-1.414l6 6a1 1 0 0 1 0 1.414l-6 6a1 1 0 0 1-1.414-1.415l4.293-4.292H6.414l4.293 4.292a1 1 0 0 1-1.414 1.415l-6-6a1 1 0 0 1 0-1.415l6-6a1 1 0 0 1 1.414 0");
}

</style>
