<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv0-ih_gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-24-regular" /></template>
<style>
.gv0-ih_gz {
  fill: currentColor;
  d: path("M2.5 3.75A.75.75 0 0 1 3.25 3h.5A2.75 2.75 0 0 1 6.5 5.75v12.5A2.75 2.75 0 0 1 3.75 21h-.5a.75.75 0 0 1 0-1.5h.5c.69 0 1.25-.56 1.25-1.25V5.75c0-.69-.56-1.25-1.25-1.25h-.5a.75.75 0 0 1-.75-.75m5.5 2A2.75 2.75 0 0 1 10.75 3h2.5A2.75 2.75 0 0 1 16 5.75v12.5A2.75 2.75 0 0 1 13.25 21h-2.5A2.75 2.75 0 0 1 8 18.25zm2.75-1.25c-.69 0-1.25.56-1.25 1.25v12.5c0 .69.56 1.25 1.25 1.25h2.5c.69 0 1.25-.56 1.25-1.25V5.75c0-.69-.56-1.25-1.25-1.25zm10-1.5a.75.75 0 0 1 0 1.5h-.5c-.69 0-1.25.56-1.25 1.25v12.5c0 .69.56 1.25 1.25 1.25h.5a.75.75 0 0 1 0 1.5h-.5a2.75 2.75 0 0 1-2.75-2.75V5.75A2.75 2.75 0 0 1 20.25 3z");
}

</style>
