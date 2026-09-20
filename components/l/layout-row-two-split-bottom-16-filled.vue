<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g0580jb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-two-split-bottom-16-filled" /></template>
<style>
.g0580jb_i {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v3h12v-3A2.5 2.5 0 0 0 11.5 2zM14 8.5H8.5V14h3a2.5 2.5 0 0 0 2.5-2.5zm-6.5 0H2v3A2.5 2.5 0 0 0 4.5 14h3z");
}

</style>
