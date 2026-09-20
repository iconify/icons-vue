<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqi7r_b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-bubble-off-rounded" /></template>
<style>
.xqi7r_b4r {
  fill: currentColor;
  d: path("M21 4.616v11.59q0 .54-.497.745t-.876-.174L6.781 3.931q-.264-.264-.126-.597Q6.792 3 7.16 3h12.225q.69 0 1.153.463T21 4.615M6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.416L1.362 2.777q-.14-.14-.15-.344t.15-.364t.354-.16t.353.16l18.554 18.554q.14.14.153.342t-.153.366q-.16.16-.354.16t-.353-.16L15.572 17z");
}

</style>
