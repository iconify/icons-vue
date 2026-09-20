<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucuzli87k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:laptop-chromebook-rounded" /></template>
<style>
.ucuzli87k {
  fill: currentColor;
  d: path("M2 18V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v13h1q.425 0 .713.288T24 19t-.288.713T23 20H1q-.425 0-.712-.288T0 19t.288-.712T1 18zm8.5 0h3q.2 0 .35-.15t.15-.35t-.15-.35t-.35-.15h-3q-.2 0-.35.15t-.15.35t.15.35t.35.15");
}

</style>
