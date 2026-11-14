<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjownlakz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-grid" /></template>
<style>
.qjownlakz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.555 5.055Q1.75 5.861 1.75 7v9.5q0 2.75 2.75 2.75H14v-1.5Q14 14 17.75 14h2.5V7q0-2.75-2.75-2.75h-2.075l-1.282-2.136q-.05-.083-.119-.151q-.07-.068-.154-.116q-.085-.048-.179-.072q-.094-.025-.191-.025h-5q-.097 0-.191.025q-.094.024-.179.072t-.154.116t-.119.151L6.575 4.25H4.5q-1.139 0-1.945.805M7.25 11.5q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5m10.5 3.75h2.5q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732t-.732-1.768v-2.5q0-2.5 2.5-2.5m.5 1.5v1.5h-1.5v-.5q0-1 1-1zm3 1q0-1-1-1h-.5v1.5h1.5zm-3 3.5v-1.5h-1.5v.5q0 .414.293.707t.707.293zm3-1.5h-1.5v1.5h.5q.414 0 .707-.293t.293-.707z");
}

</style>
