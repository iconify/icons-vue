<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iv3pg8j6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-up-right-20-filled" /></template>
<style>
.iv3pg8j6o {
  fill: currentColor;
  d: path("M9 6c.06 0-.06-.002 0 0c.023-.002.227 0 .25 0h4.393l-2.268-2.268a.75.75 0 1 1 1.061-1.06l3.353 3.352a.75.75 0 0 1 .212.639a.75.75 0 0 1-.215.443l-3.247 3.248a.75.75 0 1 1-1.06-1.061L13.27 7.5H9a3.5 3.5 0 1 0 0 7h4.25a.75.75 0 0 1 0 1.5H9A5 5 0 0 1 9 6");
}

</style>
