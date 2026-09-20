<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-j93ccjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backlight-low-rounded" /></template>
<style>
.q-j93ccjc {
  fill: currentColor;
  d: path("M3.116 14.5q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143H4.5q.213 0 .356.144t.144.357t-.144.356t-.356.143zm3.587-5.31q-.207 0-.341-.14L5.348 8.036q-.14-.14-.14-.334t.14-.335t.348-.14t.34.14L7.05 8.381q.14.14.14.335q0 .194-.14.334t-.347.14M8.5 17q-.417 0-.708-.291q-.292-.291-.292-.707t.292-.709T8.5 15h7q.417 0 .708.291q.292.291.292.707t-.292.709T15.5 17zm3.143-10.144Q11.5 6.713 11.5 6.5V5.116q0-.213.144-.357t.357-.144t.356.144t.143.356V6.5q0 .213-.144.356T11.999 7t-.356-.144m5.269 2.175q-.14-.146-.134-.354t.153-.354l.994-.975q.146-.146.354-.143t.357.168q.137.166.14.364t-.162.344l-.995.956q-.146.146-.353.153q-.208.006-.354-.16M19.5 14.5q-.213 0-.356-.144T19 13.999t.144-.356t.356-.143h1.385q.212 0 .356.144t.143.357t-.143.356t-.357.143z");
}

</style>
