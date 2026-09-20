<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el2r2mb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-hover-24-filled" /></template>
<style>
.el2r2mb1s {
  fill: currentColor;
  d: path("M4.5 4A2.5 2.5 0 0 0 2 6.5v9A2.5 2.5 0 0 0 4.5 18H9v-7.25a1.75 1.75 0 0 1 2.785-1.411l7.5 7.5c.375.275.615.679.69 1.116A2.5 2.5 0 0 0 22 15.5v-9A2.5 2.5 0 0 0 19.5 4zm6.78 6.22a.75.75 0 0 0-1.28.53v10.5a.75.75 0 0 0 1.368.425l2.467-3.588l4.26.897a.75.75 0 0 0 .685-1.264z");
}

</style>
