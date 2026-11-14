<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe1qqo3dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:case-timeline" /></template>
<style>
.xe1qqo3dr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 4q0-2.25 2.25-2.25q1.837 0 2.174 1.5h1.652q.337-1.5 2.174-1.5t2.174 1.5h1.652q.337-1.5 2.174-1.5q2.25 0 2.25 2.25T18 6.25q-1.837 0-2.174-1.5h-1.652q-.337 1.5-2.174 1.5t-2.174-1.5H8.174Q7.913 5.913 6.75 6.174V8.25H9.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v6.5q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75V11q0-2.75 2.75-2.75h.25V6.174Q3.75 5.837 3.75 4");
}

</style>
