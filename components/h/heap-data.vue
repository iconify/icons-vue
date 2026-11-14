<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joy5zrbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heap-data" /></template>
<style>
.joy5zrbps {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.25 5q0-3.25 3.25-3.25T16.75 5q0 1.47-.665 2.275l1.097 1.645q.574-.17 1.318-.17q1.346 0 2.298.952T21.75 12t-.952 2.298t-2.298.952q-3.25 0-3.25-3.25q0-1.47.665-2.275L14.818 8.08q-.574.17-1.318.17t-1.318-.17l-1.097 1.645q.665.805.665 2.275q0 1.749-.941 2.557l.762 1.271q.426-.078.929-.078q3.25 0 3.25 3.25t-3.25 3.25T9.25 19q0-1.749.941-2.557l-.762-1.271q-.426.078-.929.078t-.929-.078l-.762 1.271q.941.808.941 2.557q0 3.25-3.25 3.25q-1.346 0-2.298-.952T1.25 19q0-3.25 3.25-3.25q.503 0 .929.078l.762-1.271Q5.25 13.749 5.25 12q0-3.25 3.25-3.25q.744 0 1.318.17l1.097-1.645Q10.25 6.47 10.25 5");
}

</style>
