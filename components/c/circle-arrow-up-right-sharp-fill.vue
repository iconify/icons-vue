<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xoatxut6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-up-right-sharp-fill" /></template>
<style>
.xoatxut6x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C6.0629 1 1 6.0629 1 12C1 17.937 6.0629 23 12 23C17.937 23 23 17.937 23 12C23 6.0629 17.937 1 12 1ZM16 9L16 16L14 16L14 11.4141L9.4141 15.9998L8.0001 14.5858L12.5859 10L8 10L8 8L15 8C15.5523 8 16 8.4477 16 9Z");
}

</style>
