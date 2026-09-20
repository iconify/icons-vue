<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r1w8liblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-down-up-16-regular" /></template>
<style>
.r1w8liblu {
  fill: currentColor;
  d: path("m11.854 3.354l-3.5 3.5a.5.5 0 0 1-.708 0l-3.5-3.5a.5.5 0 1 1 .708-.708L8 5.793l3.146-3.147a.5.5 0 0 1 .708.708m0 9.292l-3.5-3.5a.5.5 0 0 0-.708 0l-3.5 3.5a.5.5 0 0 0 .708.708L8 10.207l3.146 3.147a.5.5 0 0 0 .708-.708");
}

</style>
