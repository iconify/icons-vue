<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="i4hxffrur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-brightness-1" /></template>
<style>
.i4hxffrur {
  cx: 12px;
  cy: 12px;
  r: 10px;
  fill: currentColor;
}

</style>
