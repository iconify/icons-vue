<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y8ww2_bha"/><path class="ux0qbubwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doorbell-mute" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux0qbubwi {
  d: path("M9.847 13.848q-.097.319-.097.652q0 .111.011.221t.032.218t.054.214t.074.208q.043.102.095.2q.052.097.113.189t.132.177t.148.164q.078.078.164.148q.085.07.177.132q.092.061.189.113q.098.052.2.095q.102.042.208.074t.214.054t.218.032t.221.011q.328 0 .642-.093M3.5 3.5l17 17");
}

.y8ww2_bha {
  d: path("M7.072 3.128q.028-.069.065-.133q.038-.065.085-.123q.046-.058.101-.108q.055-.051.117-.092q.061-.042.129-.074q.067-.032.138-.054t.145-.033T8 2.5h8q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T17 3.5v9.586m-.084 7.816q-.029.066-.068.127q-.038.062-.085.117t-.101.104q-.054.048-.115.087q-.061.04-.126.07q-.066.031-.136.051q-.069.021-.141.032T16 21.5H8q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T7 20.5v-9.557M10.9 7h2.6");
}

</style>
