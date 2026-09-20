<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t94zek50p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:data-table-rounded" /></template>
<style>
.t94zek50p {
  fill: currentColor;
  d: path("M4 8.923h16V5.981q0-.505-.353-.858q-.354-.354-.858-.354H5.211q-.505 0-.859.353Q4 5.477 4 5.982zm0 5.154h16V9.923H4zm1.212 5.154h13.577q.504 0 .858-.354q.353-.353.353-.858v-2.942H4v2.942q0 .505.353.859q.354.353.859.353m.787-11.81q-.23-.233-.23-.578t.234-.575t.577-.23t.575.234t.23.578t-.233.574t-.578.23t-.575-.233m0 5.154q-.23-.234-.23-.578q0-.345.234-.575q.233-.23.577-.23t.575.234t.23.577t-.233.575t-.578.23t-.575-.233m0 5.153q-.23-.233-.23-.577t.234-.575t.577-.23t.575.233q.23.234.23.578t-.233.575q-.234.23-.578.23t-.575-.234");
}

</style>
