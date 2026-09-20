<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni39i-ivg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:divider-tall-24-filled" /></template>
<style>
.ni39i-ivg {
  fill: currentColor;
  d: path("M11 3v18a1 1 0 1 0 2 0V3a1 1 0 1 0-2 0");
}

</style>
