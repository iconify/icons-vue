<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vtlcqibob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bidirectional-left-right-32-light" /></template>
<style>
.vtlcqibob {
  fill: currentColor;
  d: path("M20.647 7.646a.5.5 0 0 1 .707 0l7.5 7.5a.5.5 0 0 1 0 .707l-7.5 7.5a.5.5 0 1 1-.707-.707L27.293 16H4.707l6.647 6.647a.5.5 0 0 1-.707.707l-7.5-7.5a.5.5 0 0 1 0-.707l7.5-7.5a.5.5 0 1 1 .707.707L4.707 15h22.586l-6.646-6.646a.5.5 0 0 1 0-.708");
}

</style>
