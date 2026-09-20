<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eqflmlbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-ribbon-48-filled" /></template>
<style>
.eqflmlbir {
  fill: currentColor;
  d: path("M17 44.958c0 .85-.964 1.34-1.651.84L11.5 43l-3.849 2.799A1.04 1.04 0 0 1 6 44.958v-6.71A9.5 9.5 0 0 0 11.5 40a9.5 9.5 0 0 0 5.5-1.754zm7-29.708A3.75 3.75 0 0 0 27.75 19H40v22a3 3 0 0 1-3 3H19v-7.668a9.46 9.46 0 0 0 2-5.832a9.5 9.5 0 0 0-9.5-9.5a9.5 9.5 0 0 0-3.5.665V7a3 3 0 0 1 3-3h13zM11.5 23a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15m27.962-6.5H27.75c-.69 0-1.25-.56-1.25-1.25V4.464z");
}

</style>
