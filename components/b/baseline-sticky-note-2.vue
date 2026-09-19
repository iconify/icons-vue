<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnpfpe3_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-sticky-note-2" /></template>
<style>
.gnpfpe3_u {
  fill: currentColor;
  d: path("M19 3H4.99C3.89 3 3 3.9 3 5l.01 14c0 1.1.89 2 1.99 2h10l6-6V5c0-1.1-.9-2-2-2M7 8h10v2H7zm5 6H7v-2h5zm2 5.5V14h5.5z");
}

</style>
