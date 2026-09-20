<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6tbwxblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-windows-rounded" /></template>
<style>
.w6tbwxblk {
  fill: currentColor;
  d: path("M1.5 18.77q-.213 0-.357-.144T1 18.269t.143-.356t.357-.144h3.116V17q-.691 0-1.153-.462T3 15.385v-8.77q0-.69.463-1.152T4.615 5h14.77q.69 0 1.152.463T21 6.615v8.77q0 .69-.463 1.153T19.385 17v.77H22.5q.214 0 .357.143t.143.356t-.143.357t-.357.143z");
}

</style>
