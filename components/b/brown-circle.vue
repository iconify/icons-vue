<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="jyo12bpqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:brown-circle" /></template>
<style>
.jyo12bpqb {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--c1694f, #c1694f);
}

</style>
