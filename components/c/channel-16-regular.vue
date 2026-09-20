<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="img7lo4dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:channel-16-regular" /></template>
<style>
.img7lo4dr {
  fill: currentColor;
  d: path("M2.5 6.55a.998.998 0 1 1 0-1.996a.998.998 0 0 1 0 1.996m-.325-2.97a2 2 0 0 1 1.06.113A1.5 1.5 0 0 1 4.5 3h7A1.5 1.5 0 0 1 13 4.5v7a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 11.5V7.487a2 2 0 0 1-1 0V11.5A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2h-7a2.5 2.5 0 0 0-2.325 1.58M6 6a.5.5 0 0 0 0 1h4a.5.5 0 1 0 0-1zm0 3a.5.5 0 0 0 0 1h2.614a.5.5 0 0 0 0-1z");
}

</style>
