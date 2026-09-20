<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tjo2dwbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:building-retail-more-32-filled" /></template>
<style>
.tjo2dwbfv {
  fill: currentColor;
  d: path("M6.13 4.087A3 3 0 0 1 8.441 3H23.56a3 3 0 0 1 2.312 1.087l4.665 5.638c1.079 1.304.151 3.275-1.541 3.275H3.005c-1.692 0-2.62-1.971-1.54-3.275zM4 15v10.75A3.25 3.25 0 0 0 7.25 29h17.5A3.25 3.25 0 0 0 28 25.75V15zm8 5a2 2 0 1 1-4 0a2 2 0 0 1 4 0m4 2a2 2 0 1 1 0-4a2 2 0 0 1 0 4m8-2a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
