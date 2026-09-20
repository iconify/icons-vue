<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sog1mj1vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:earbud-left" /></template>
<style>
.sog1mj1vz {
  fill: currentColor;
  d: path("M8 22q-.825 0-1.412-.587T6 20v-8H5q-.825 0-1.412-.587T3 10V6q0-.825.588-1.412T5 4h7v16q0 .825-.587 1.413T10 22zm6-8V2h1q2.5 0 4.25 1.75T21 8t-1.75 4.25T15 14z");
}

</style>
