<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b-nlkacko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:color-line-accent-20-regular" /></template>
<style>
.b-nlkacko {
  fill: currentColor;
  d: path("M4.095 13a1.497 1.497 0 0 0 1.772.952l3.112-.767l.21-.064l.025-.009q.132-.05.26-.112H16a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1z");
}

</style>
