<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr0v3vbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:file-copy" /></template>
<style>
.wr0v3vbok {
  fill: currentColor;
  d: path("M4 23q-.825 0-1.412-.587T2 21V7h2v14h11v2zm4-4q-.825 0-1.412-.587T6 17V3q0-.825.588-1.412T8 1h7l6 6v10q0 .825-.587 1.413T19 19zm6-11h5l-5-5z");
}

</style>
