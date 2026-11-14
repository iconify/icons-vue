<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k9w6_hbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bidirectional-up-down-32-light" /></template>
<style>
.k9w6_hbal {
  fill: currentColor;
  d: path("M15.147 3.146a.5.5 0 0 1 .707 0l7.5 7.5a.5.5 0 0 1-.707.707L16 4.708v22.586l6.647-6.646a.5.5 0 1 1 .707.707l-7.5 7.5a.5.5 0 0 1-.707 0l-7.5-7.5a.5.5 0 1 1 .706-.707L15 27.293V4.707l-6.647 6.647a.5.5 0 1 1-.707-.707z");
}

</style>
