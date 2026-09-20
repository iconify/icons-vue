<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f94gndsto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:aod-tablet" /></template>
<style>
.f94gndsto {
  fill: currentColor;
  d: path("M8 11.5V10h8v1.5zm1 3V13h6v1.5zM3 20q-.825 0-1.412-.587T1 18V6q0-.825.588-1.412T3 4h18q.825 0 1.413.588T23 6v12q0 .825-.587 1.413T21 20zm3-2h12V6H6z");
}

</style>
