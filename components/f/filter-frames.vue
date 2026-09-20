<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al9rxtcrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-frames" /></template>
<style>
.al9rxtcrk {
  fill: currentColor;
  d: path("M4 22q-.825 0-1.412-.587T2 20V6q0-.825.588-1.412T4 4h4l4-4l4 4h4q.825 0 1.413.588T22 6v14q0 .825-.587 1.413T20 22zm0-2h16V6H4zm2-2V8h12v10z");
}

</style>
