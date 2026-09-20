<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l2nusvbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-down-left-24-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l2nusvbpn {
  d: path("M16.5 7.811l-8.69 8.69h8.44a.25.25 0 0 0 .25-.25V7.81zm-.634-1.487c.788-.788 2.134-.23 2.134.884v9.042A1.75 1.75 0 0 1 16.25 18H7.207c-1.114 0-1.671-1.346-.884-2.133l9.543-9.543z");
  fill: currentColor;
}

</style>
