<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvdugylzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fight-camp" /></template>
<style>
.nvdugylzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.284 20.5H4.83q-.047 0-.094-.003q-.046-.003-.093-.009q-.046-.005-.092-.014l-.092-.02l-.09-.026l-.088-.032q-.044-.017-.086-.037l-.084-.042q-.041-.022-.08-.047q-.04-.025-.078-.053t-.074-.057t-.071-.061q-.034-.032-.066-.066q-.033-.034-.063-.07t-.058-.074q-.027-.037-.053-.077q-.025-.039-.048-.08t-.043-.083t-.038-.086t-.032-.088t-.027-.089q-.012-.046-.021-.092t-.016-.092q-.006-.046-.01-.093l-.004-.094q0-.047.002-.093l.008-.094l.014-.092q.008-.046.019-.092q.011-.045.025-.09t.031-.089l.036-.086l5.17-11.375q.044-.098.102-.188q.058-.091.129-.172q.07-.082.151-.152q.081-.071.171-.129t.189-.103q.097-.045.201-.075q.103-.031.209-.046T10 6.124t.214.015t.209.046t.201.075t.189.103t.171.129t.151.152t.129.172t.102.188l3.25 7.151M10 4V2.5m0 9.5v8.5m7.75-4.75h2.5A1.75 1.75 0 0 1 22 17.5v2.25a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 16 19.75V17.5a1.75 1.75 0 0 1 1.75-1.75M16 18h6m-4.25-3.25v1.5m2.5-1.5v1.5");
}

</style>
