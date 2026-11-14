<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oz1jqt5tb"/><path class="zrj95_b-r"/><path class="ee2uswqts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-drop" /></template>
<style>
.ee2uswqts {
  d: path("M3 10.5q0 .111.025.221t.076.218q.05.108.125.214t.174.208t.22.2t.265.189t.307.177t.346.164t.381.148q.2.07.414.132q.215.061.442.113q.228.052.466.095q.238.042.485.074t.5.054t.509.032t.515.011q.791 0 1.548-.1q.756-.1 1.41-.291m1.429-.623q.21-.137.372-.286q.161-.148.271-.305q.109-.157.165-.319q.055-.162.055-.326m.5 4h8m-5.5 0v-1.25h3v1.25m-4.5 0l1 7h4l1-7");
}

.oz1jqt5tb {
  d: path("M3 5a5.25 2.25 0 1 0 10.5 0A5.25 2.25 0 1 0 3 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrj95_b-r {
  d: path("M3 5v11q0 .111.025.221t.076.218q.05.108.125.214t.174.208t.22.2t.265.189t.307.177t.346.164t.381.148q.2.07.414.132q.215.061.442.113q.228.052.466.095q.238.042.485.074t.5.054t.509.032t.515.011q.313 0 .623-.016q.311-.016.615-.047q.304-.032.597-.079t.571-.108q.278-.062.537-.137t.496-.163t.447-.187t.391-.208m.973-5.639V5");
}

</style>
