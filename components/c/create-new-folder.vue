<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-ttmvkju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:create-new-folder" /></template>
<style>
.r-ttmvkju {
  fill: currentColor;
  d: path("M14 16h2v-2h2v-2h-2v-2h-2v2h-2v2h2zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20z");
}

</style>
