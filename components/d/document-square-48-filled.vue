<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tyh-7jbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-square-48-filled" /></template>
<style>
.tyh-7jbyy {
  fill: currentColor;
  d: path("M26 17.75A4.25 4.25 0 0 0 30.25 22H42v15.75A4.25 4.25 0 0 1 37.75 42h-27.5A4.25 4.25 0 0 1 6 37.75v-27.5A4.25 4.25 0 0 1 10.25 6H26zm2.5-11.375c.466.21.895.502 1.263.87l10.992 10.992c.368.368.66.797.869 1.263H30.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
