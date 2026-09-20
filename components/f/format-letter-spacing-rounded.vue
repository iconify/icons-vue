<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3wgg2b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-letter-spacing-rounded" /></template>
<style>
.j3wgg2b6y {
  fill: currentColor;
  d: path("m7.114 18.212l1.746 1.765q.14.14.14.341t-.146.347q-.14.16-.354.15t-.354-.15l-2.388-2.388q-.243-.243-.243-.566t.243-.565l2.388-2.369q.14-.14.341-.15q.202-.01.367.15q.165.165.165.357t-.165.356l-1.74 1.721h9.753l-1.726-1.727q-.141-.14-.15-.34q-.01-.202.155-.367q.16-.16.354-.16t.354.16l2.369 2.37q.243.241.243.564t-.243.566l-2.388 2.388q-.14.14-.342.15q-.2.01-.366-.15q-.165-.165-.165-.356q0-.192.165-.357l1.74-1.74zm-.97-6.855Q6 11.214 6 11V3.5q0-.213.143-.357T6.5 3t.357.143T7 3.5V11q0 .214-.143.357T6.5 11.5t-.357-.143m5.5 0Q11.5 11.214 11.5 11V3.5q0-.213.143-.357T12 3t.357.143t.143.357V11q0 .214-.143.357T12 11.5t-.357-.143m5.5 0Q17 11.214 17 11V3.5q0-.213.143-.357T17.5 3t.357.143T18 3.5V11q0 .214-.143.357t-.357.143t-.357-.143");
}

</style>
