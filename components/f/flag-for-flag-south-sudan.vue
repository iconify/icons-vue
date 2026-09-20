<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="onz9krbfs"/><path class="e4p4mvv5u"/><path class="pu2zrobcl"/><path class="yzp940bvv"/><path class="bvqy5g6go"/><path class="p2cf260yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-south-sudan" /></template>
<style>
.bvqy5g6go {
  fill: var(--svg-color--0f47af, #0F47AF);
  d: path("M1.351 6.004H1.35C.522 6.737 0 7.808 0 9.267v18c0 .926.522 1.997 1.351 2.729L17.5 18L1.351 6.004z");
}

.e4p4mvv5u {
  fill: var(--svg-color--078930, #078930);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-3H0v3z");
}

.onz9krbfs {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v3h36V9a4 4 0 0 0-4-4z");
}

.p2cf260yt {
  fill: var(--svg-color--fcdd09, #FCDD09);
  d: path("M8.249 17.917l1.777-2.446l-2.875.934l-1.776-2.445v3.023l-2.875.934l2.875.934v3.022l1.776-2.445l2.875.934z");
}

.pu2zrobcl {
  fill: var(--svg-color--da121a, #DA121A);
  d: path("M0 12h36v12H0z");
}

.yzp940bvv {
  d: path("M0 12h36v2H0zm0 10h36v2H0z");
  fill: var(--svg-color--eee, #EEE);
}

</style>
