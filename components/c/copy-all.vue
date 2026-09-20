<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcjzatbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:copy-all" /></template>
<style>
.tcjzatbii {
  fill: currentColor;
  d: path("M3 18.5v-2h2v2zM3 15v-2h2v2zm0-3.5v-2h2v2zM6.5 22v-2h2v2zM9 18q-.825 0-1.412-.587T7 16V4q0-.825.588-1.412T9 2h9q.825 0 1.413.588T20 4v12q0 .825-.587 1.413T18 18zm1 4v-2h2v2zm-5 0q-.825 0-1.412-.587T3 20h2zm8.5 0v-2h2q0 .825-.587 1.413T13.5 22M3 8q0-.825.588-1.412T5 6v2z");
}

</style>
