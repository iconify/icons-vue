<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1b2gxcau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:detector-status-outline-sharp" /></template>
<style>
.y1b2gxcau {
  fill: currentColor;
  d: path("M10.95 20.039L8.112 17.2l.713-.688l2.125 2.125l4.225-4.25l.713.713zM5 5v1.77h14V5zm2.523 2.77l.646 1.769h7.662l.646-1.77zm-.092 2.769l-.97-2.77H4V4h16v3.77h-2.461l-1.074 2.769zM5 5v1.77z");
}

</style>
