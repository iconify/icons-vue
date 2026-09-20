<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpotcvbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:east-outline-rounded" /></template>
<style>
.cpotcvbxq {
  fill: currentColor;
  d: path("M18.175 13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h15.175L14.3 7.1q-.275-.275-.288-.687T14.3 5.7q.275-.275.7-.275t.7.275l5.6 5.6q.15.15.213.325t.062.375t-.062.375t-.213.325l-5.6 5.6q-.275.275-.687.275T14.3 18.3q-.3-.3-.3-.712t.3-.713z");
}

</style>
