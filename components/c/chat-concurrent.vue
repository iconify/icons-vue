<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdwtjpbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-concurrent" /></template>
<style>
.gdwtjpbfy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.75 13.5v-.75H19q2.75 0 2.75-2.75V6q0-2.75-2.75-2.75h-7.5Q8.75 3.25 8.75 6v.75H8.5q-2.75 0-2.75 2.75v.75H5.5q-1.139 0-1.945.805q-.805.806-.805 1.945v4q0 2.345 2 2.69V21q0 .227.126.416q.041.061.093.114q.052.052.114.093q.061.041.129.07q.068.028.141.042t.146.015q.074 0 .147-.014q.072-.015.14-.043t.13-.069l2.811-1.874H13q2.75 0 2.75-2.75v-.75H16q2.75 0 2.75-2.75M10.25 6v.75H16q2.75 0 2.75 2.75v1.75H19q1.25 0 1.25-1.25V6q0-1.25-1.25-1.25h-7.5q-1.25 0-1.25 1.25M8.5 8.25H16q1.25 0 1.25 1.25v4q0 1.25-1.25 1.25h-.25V13q0-2.75-2.75-2.75H7.25V9.5q0-1.25 1.25-1.25");
}

</style>
