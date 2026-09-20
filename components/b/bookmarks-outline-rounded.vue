<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yob6d49ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmarks-outline-rounded" /></template>
<style>
.yob6d49ic {
  fill: currentColor;
  d: path("M10.154 18.346L6.18 20.391q-.404.211-.792-.019q-.389-.23-.389-.69V8.463q0-.672.472-1.144t1.143-.472h7.058q.671 0 1.143.472q.473.472.473 1.143v11.222q0 .46-.389.689q-.388.23-.792.019zM6 19.398l3.396-1.784q.354-.193.748-.193t.748.192l3.396 1.785V8.462q0-.27-.172-.443q-.174-.173-.443-.173H6.616q-.27 0-.443.173T6 8.461zm12.143-2.099Q18 17.156 18 16.942V4.616q0-.27-.173-.443T17.385 4H8.289q-.214 0-.357-.143T7.789 3.5t.143-.357T8.289 3h9.096q.67 0 1.143.472q.472.472.472 1.144v12.326q0 .214-.143.357t-.357.143t-.357-.143M6 7.846h8.289z");
}

</style>
