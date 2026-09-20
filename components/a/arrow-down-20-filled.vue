<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o4wjk3b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-20-filled" /></template>
<style>
.o4wjk3b2p {
  fill: currentColor;
  d: path("M16.792 11.265a.75.75 0 0 0-1.09-1.03l-4.955 5.239V2.75a.75.75 0 0 0-1.5 0v12.726L4.29 10.235a.75.75 0 0 0-1.09 1.03l6.07 6.418a1 1 0 0 0 .566.3a.75.75 0 0 0 .329-.002a1 1 0 0 0 .558-.298z");
}

</style>
