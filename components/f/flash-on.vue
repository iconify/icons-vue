<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6ekypzqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:flash-on" /></template>
<style>
.k6ekypzqk {
  fill: currentColor;
  d: path("M7 2v11h3v9l7-12h-4l4-8z");
}

</style>
