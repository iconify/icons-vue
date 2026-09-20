<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d--0jebvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-bubble-off-outline-rounded" /></template>
<style>
.d--0jebvv {
  fill: currentColor;
  d: path("M21 4.616v11.623q0 .213-.143.356t-.357.143q-.183 0-.341-.125T20 16.238V4.616q0-.27-.173-.443T19.385 4H7.064q-.25 0-.375-.159q-.125-.158-.125-.341t.125-.341T7.064 3h12.32q.691 0 1.154.463T21 4.616M6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.416L1.362 2.777q-.14-.14-.15-.344t.15-.364t.354-.16t.353.16l18.554 18.554q.14.14.153.342t-.153.366q-.16.16-.354.16t-.353-.16L15.572 17zM4 5.416v12.228L5.65 16h8.935z");
}

</style>
