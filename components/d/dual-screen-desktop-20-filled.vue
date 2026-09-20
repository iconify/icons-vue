<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c33za5uaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-desktop-20-filled" /></template>
<style>
.c33za5uaq {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-2v2h1a.5.5 0 0 1 0 1h-2v-6a3 3 0 0 0-3-3H4zm6 14H7.5V8H10a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2M4 8h2.5v10H4a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2m5.5 7a.5.5 0 0 0 0 1h.5a.5.5 0 0 0 0-1zm-6 .5a.5.5 0 0 0 .5.5h.5a.5.5 0 0 0 0-1H4a.5.5 0 0 0-.5.5");
}

</style>
