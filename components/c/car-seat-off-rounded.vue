<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfj7upjnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:car-seat-off-rounded" /></template>
<style>
.wfj7upjnf {
  fill: currentColor;
  d: path("M9.594 6.692L7.366 4.45q.159-.113.364-.185q.205-.073.424-.073q.69 0 1.191.501t.501 1.192q0 .219-.069.433t-.183.374M9.766 18q-.552 0-.946-.332t-.504-.845l-1.177-5.62q-.12-.614.096-1.112q.215-.499.619-.822L2.446 3.862q-.14-.14-.15-.345q-.01-.203.15-.363t.354-.16t.354.16l17.692 17.692q.14.14.15.345q.01.203-.15.363t-.354.16t-.353-.16L16.585 18z");
}

</style>
