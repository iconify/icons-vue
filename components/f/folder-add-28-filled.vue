<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ztcpd1r6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-add-28-filled" /></template>
<style>
.ztcpd1r6g {
  fill: currentColor;
  d: path("M2 6.75A3.75 3.75 0 0 1 5.75 3h3.672c.729 0 1.428.29 1.944.805L13.25 5.69l-2.944 2.945A1.25 1.25 0 0 1 9.422 9H2zm.004 3.75v9.75A3.75 3.75 0 0 0 5.754 24H14.5A7.5 7.5 0 0 1 26 14.401V9.75A3.75 3.75 0 0 0 22.25 6h-7.19l-3.695 3.695a2.75 2.75 0 0 1-1.944.805zM27 19.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0m-6-4a.5.5 0 0 0-1 0V19h-3.5a.5.5 0 0 0 0 1H20v3.5a.5.5 0 0 0 1 0V20h3.5a.5.5 0 0 0 0-1H21z");
}

</style>
