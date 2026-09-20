<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt64c31ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-h6" /></template>
<style>
.tt64c31ag {
  fill: currentColor;
  d: path("M3 17V7h2v4h4V7h2v10H9v-4H5v4zm12 0q-.825 0-1.412-.587T13 15V9q0-.825.588-1.412T15 7h6v2h-6v2h4q.825 0 1.413.588T21 13v2q0 .825-.587 1.413T19 17zm0-4v2h4v-2z");
}

</style>
