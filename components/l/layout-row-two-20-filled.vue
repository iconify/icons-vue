<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s9x4u3bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-20-filled" /></template>
<style>
.s9x4u3bnz {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v3.5H3zm0 4.5V14a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3v-3.5z");
}

</style>
