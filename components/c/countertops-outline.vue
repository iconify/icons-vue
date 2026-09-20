<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if6_2accr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:countertops-outline" /></template>
<style>
.if6_2accr {
  fill: currentColor;
  d: path("M4 20v-8H2v-2h4q-.825 0-1.412-.587T4 8V4h6v4q0 .825-.587 1.413T8 10h8V7q0-.425-.288-.712T15 6t-.712.288T14 7h-2q0-1.25.875-2.125T15 4t2.125.875T18 7v3h4v2h-2v8zM6 8h2V6H6zm0 10h5v-6H6zm7 0h5v-6h-5zM6 8h2zm0 10h12z");
}

</style>
