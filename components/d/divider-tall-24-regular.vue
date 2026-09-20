<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8c_5d7bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:divider-tall-24-regular" /></template>
<style>
.t8c_5d7bh {
  fill: currentColor;
  d: path("M11.25 2.75v18.5a.75.75 0 0 0 1.5 0V2.75a.75.75 0 0 0-1.5 0");
}

</style>
