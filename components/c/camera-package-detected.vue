<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw0ta4xgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-package-detected" /></template>
<style>
.cw0ta4xgh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.555 5.055Q1.75 5.861 1.75 7v9.5q0 2.75 2.75 2.75H14V17q0-3.5 3.5-3.5h2.75V7q0-2.75-2.75-2.75h-2.075l-1.282-2.136q-.05-.083-.119-.151q-.07-.068-.154-.116q-.085-.048-.179-.072q-.094-.025-.191-.025h-5q-.097 0-.191.025q-.094.024-.179.072t-.154.116t-.119.151L6.575 4.25H4.5q-1.139 0-1.945.805M7.25 11.5q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5m13.25 3.25h-3q-2.25 0-2.25 2.25v3.5q0 2.25 2.25 2.25h3q2.25 0 2.25-2.25V17q0-2.25-2.25-2.25m-3.75 2.75V17q0-.75.75-.75h3q.75 0 .75.75v.5zm0 3V19h4.5v1.5q0 .75-.75.75h-3q-.75 0-.75-.75");
}

</style>
