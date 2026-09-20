<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tje94m44w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:eraser-small-24-filled" /></template>
<style>
.tje94m44w {
  fill: currentColor;
  d: path("M12.651 2.638a2.25 2.25 0 0 1 3.19.023l4.91 5.008a2.25 2.25 0 0 1-.007 3.158l-2.257 2.281a4.5 4.5 0 0 0-5.368 5.424l-1.784 1.803a2.25 2.25 0 0 1-3.176.023l-5.1-5.008a2.25 2.25 0 0 1-.006-3.204zM4.108 13.212a.75.75 0 0 0 .003 1.068l5.099 5.008a.75.75 0 0 0 1.058-.008l1.468-1.483l-6.099-6.1zM17.5 21a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

</style>
