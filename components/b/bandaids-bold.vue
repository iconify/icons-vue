<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tfzi9bb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bandaids-bold" /></template>
<style>
.tfzi9bb7o {
  fill: currentColor;
  d: path("m190.23 128l24.88-24.89a44 44 0 1 0-62.22-62.22L128 65.77l-24.89-24.88a44 44 0 1 0-62.22 62.22L65.77 128l-24.88 24.89a44 44 0 1 0 62.22 62.22L128 190.23l24.89 24.88a44 44 0 1 0 62.22-62.22Zm-20.37-70.14a20 20 0 1 1 28.28 28.28L173.25 111L145 82.75ZM156.28 128L128 156.28L99.72 128L128 99.72ZM57.86 86.14a20 20 0 1 1 28.28-28.28L111 82.75L82.75 111Zm28.28 112a20 20 0 1 1-28.28-28.28L82.75 145L111 173.25Zm112 0a20 20 0 0 1-28.28 0L145 173.25L173.25 145l24.89 24.89a20 20 0 0 1 0 28.28Z");
}

</style>
