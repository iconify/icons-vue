<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xos-rb_hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-check" /></template>
<style>
.xos-rb_hl {
  fill: currentColor;
  d: path("M10.85 16.575L16.5 10.9l-1.4-1.4l-4.25 4.25l-2.125-2.125L7.3 13.05zM4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20z");
}

</style>
