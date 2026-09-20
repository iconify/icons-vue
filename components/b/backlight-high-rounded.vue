<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_9dqem5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backlight-high-rounded" /></template>
<style>
.c_9dqem5j {
  fill: currentColor;
  d: path("M2.116 14.5q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143H4.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zm4.587-5.31q-.207 0-.341-.14L4.61 7.298q-.14-.13-.14-.327q0-.196.136-.342q.149-.146.347-.146q.199 0 .345.146L7.05 8.38q.14.14.14.335q0 .194-.14.334t-.347.14M8.5 17q-.417 0-.708-.291q-.292-.291-.292-.707t.292-.709T8.5 15h7q.417 0 .708.291q.292.291.292.707t-.292.709T15.5 17zm3.143-10.144Q11.5 6.713 11.5 6.5V3.116q0-.213.144-.357t.357-.143t.356.143t.143.357V6.5q0 .213-.144.356T11.999 7t-.356-.144m5.269 2.185q-.14-.15-.131-.364q.01-.213.15-.354l1.733-1.694q.14-.14.35-.15q.211-.01.357.15q.146.146.137.354q-.01.208-.156.354L17.619 9.03q-.14.14-.353.15q-.214.01-.354-.14M19.5 14.5q-.213 0-.356-.144T19 13.999t.144-.356t.356-.143h2.385q.212 0 .356.144t.143.357t-.143.356t-.357.143z");
}

</style>
