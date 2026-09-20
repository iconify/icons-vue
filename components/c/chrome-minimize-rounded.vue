<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gripr69wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-minimize-rounded" /></template>
<style>
.gripr69wu {
  fill: currentColor;
  d: path("M5 20q-.425 0-.713-.288T4 19q0-.425.288-.713T5 18h14q.425 0 .713.288T20 19q0 .425-.288.713T19 20H5Z");
}

</style>
