<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r5cmul4eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-swap-16-regular" /></template>
<style>
.r5cmul4eu {
  fill: currentColor;
  d: path("M10.354 1.646a.5.5 0 0 0-.708.708L11.293 4H3.5a.5.5 0 0 0 0 1h7.793L9.646 6.646a.5.5 0 1 0 .708.708l2.5-2.5a.5.5 0 0 0 0-.708zm-4 7.708a.5.5 0 1 0-.708-.708l-2.5 2.5a.5.5 0 0 0 0 .708l2.5 2.5a.5.5 0 0 0 .708-.708L4.707 12H12.5a.5.5 0 0 0 0-1H4.707z");
}

</style>
