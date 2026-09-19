<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xf78a_b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:heavy-check-mark" /></template>
<style>
.xf78a_b-m {
  fill: var(--svg-color--4d5357, #4d5357);
  d: path("M56 2L18.8 42.9L8 34.7H2L18.8 62L62 2z");
}

</style>
