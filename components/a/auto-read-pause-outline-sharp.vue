<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3efcqb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-read-pause-outline-sharp" /></template>
<style>
.n3efcqb2h {
  fill: currentColor;
  d: path("M9 14h2V6H9zm4 0h2V6h-2zM2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
