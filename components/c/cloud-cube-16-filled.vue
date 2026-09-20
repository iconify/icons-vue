<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i3naad4kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-cube-16-filled" /></template>
<style>
.i3naad4kd {
  fill: currentColor;
  d: path("M8 2a4 4 0 0 0-3.97 3.507A3.25 3.25 0 0 0 4.25 12H6V8.5a2 2 0 0 1 1.106-1.789l3-1.5a2 2 0 0 1 1.788 0l.031.016A4 4 0 0 0 8 2m6.447 5.606l-3-1.5a1 1 0 0 0-.894 0l-3 1.5A1 1 0 0 0 7 8.5v4.004a1 1 0 0 0 .553.894l3 1.5a1 1 0 0 0 .894 0l3-1.5a1 1 0 0 0 .553-.894V8.5a1 1 0 0 0-.553-.894M8.04 8.732a.5.5 0 0 1 .657-.263L11 9.456l2.303-.987a.5.5 0 0 1 .394.92l-2.197.94V13a.5.5 0 1 1-1 0v-2.67l-2.197-.942a.5.5 0 0 1-.263-.656");
}

</style>
