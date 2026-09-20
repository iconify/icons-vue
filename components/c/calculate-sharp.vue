<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nawujrbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calculate-sharp" /></template>
<style>
.nawujrbcj {
  fill: currentColor;
  d: path("M8.308 17.692h.884v-2h2v-.884h-2v-2h-.884v2h-2v.884h2zm5-.75h4.384v-.884h-4.384zm0-2.5h4.384v-.884h-4.384zm-6.75-5.55h4.384v-.884H6.558zM4 20V4h16v16zm10.1-9.511l1.4-1.4l1.4 1.4l.627-.628l-1.4-1.411l1.4-1.4l-.627-.627l-1.4 1.4l-1.4-1.4l-.627.627l1.4 1.4l-1.4 1.412z");
}

</style>
