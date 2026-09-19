<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xcnd_lbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:argenta" /></template>
<style>
.xcnd_lbdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.797 16.203H13.321L4.5 23.182v12.649l8.821 6.98h12.476l8.821-6.98V23.182zm8.821 12.467L16.746 42.811M29.91 19.457L6.857 37.696m10.811-21.493L4.5 26.622m31.387-12.623L43.5 7.976H28.067l-7.613 6.023zm-15.433 0v-8.81");
}

</style>
