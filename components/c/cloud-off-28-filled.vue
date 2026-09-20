<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="t8bt0kmia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-off-28-filled" /></template>
<style>
.t8bt0kmia {
  fill: currentColor;
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06l5.54 5.542a7 7 0 0 0-.692 2.195A5.5 5.5 0 0 0 7.5 22h13q.213 0 .423-.016l3.796 3.796a.75.75 0 0 0 1.061-1.06zm6.396 4.275l14.282 14.282a5.5 5.5 0 0 0-3.027-9.76A7.001 7.001 0 0 0 9.676 6.495");
}

</style>
