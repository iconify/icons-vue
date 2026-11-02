<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g047skb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:container-fill" /></template>
<style>
.g047skb_b {
  fill: currentColor;
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm7 9V8a1 1 0 0 0-2 0v8a1 1 0 0 0 2 0m4 0V8a1 1 0 0 0-2 0v8a1 1 0 0 0 2 0m4-8a1 1 0 0 0-2 0v8a1 1 0 0 0 2 0Z");
}

</style>
