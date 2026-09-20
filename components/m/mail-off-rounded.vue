<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zydif19lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mail-off-rounded" /></template>
<style>
.zydif19lh {
  fill: currentColor;
  d: path("M20.075 21.496L17.573 19H4.616q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5H5l1 1H4.573L2.959 4.386q-.145-.146-.155-.347t.156-.366t.356-.165q.192 0 .357.165l17.116 17.116q.145.145.155.344t-.155.363t-.357.165t-.357-.165m-.029-4.46q-.227-.028-.419-.22l-5.848-5.849l5.898-3.87q.196-.13.217-.304t-.077-.334t-.269-.211t-.367.077L13.11 10.3L9.185 6.373q-.192-.192-.22-.42q-.028-.226.059-.443q.087-.218.273-.364T9.756 5h9.629q.69 0 1.153.463T21 6.616v9.628q0 .273-.146.46q-.146.186-.363.273q-.218.087-.445.059");
}

</style>
