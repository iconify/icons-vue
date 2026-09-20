<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krn4gbc1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hd-16-regular" /></template>
<style>
.krn4gbc1u {
  fill: currentColor;
  d: path("M4.5 5a.5.5 0 0 1 .5.5V8h1.5V5.5a.5.5 0 0 1 1 0v5a.5.5 0 0 1-1 0V9H5v1.5a.5.5 0 0 1-1 0v-5a.5.5 0 0 1 .5-.5M9 5a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 .5.5h.417A2.583 2.583 0 0 0 12 8.417v-.834A2.583 2.583 0 0 0 9.417 5zm2 3.417c0 .846-.664 1.538-1.5 1.58V6.003c.836.043 1.5.735 1.5 1.581zM2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM4.5 3A1.5 1.5 0 0 0 3 4.5v7A1.5 1.5 0 0 0 4.5 13h7a1.5 1.5 0 0 0 1.5-1.5v-7A1.5 1.5 0 0 0 11.5 3z");
}

</style>
