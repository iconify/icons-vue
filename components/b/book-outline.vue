<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfa8sizmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:book-outline" /></template>
<style>
.kfa8sizmm {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm0-2h12V4h-2v7l-2.5-1.5L11 11V4H6zm0 0V4zm5-9l2.5-1.5L16 11l-2.5-1.5z");
}

</style>
