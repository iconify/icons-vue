<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njcu9mbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-help-corner-fill" /></template>
<style>
.njcu9mbne {
  fill: currentColor;
  d: path("M9.414 10L3.707 4.292A3 3 0 0 1 5 4h14c.448 0 .889.099 1.293.292L14.586 10ZM22 11a1 1 0 0 1-.999 1a5.01 5.01 0 0 0-5.006-.581l5.713-5.712c.193.404.292.845.292 1.293ZM3.068 6.482l4.639 4.639A3 3 0 0 0 9.828 12H12v7a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V7c0-.448.099-.889.292-1.293ZM15 16a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 17 16a1 1 0 0 1-2 0m3 4h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

</style>
