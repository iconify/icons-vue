<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqzdrxbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:book-rounded" /></template>
<style>
.bqzdrxbll {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4v16q0 .825-.587 1.413T18 22zm5-18v6.125q0 .3.238.438t.512-.013l1.225-.725q.25-.15.513-.15t.512.15l1.225.725q.275.15.525.013t.25-.438V4z");
}

</style>
