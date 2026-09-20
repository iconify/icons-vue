<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh-by5bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:cake" /></template>
<style>
.yh-by5bwj {
  fill: currentColor;
  d: path("M4.73 21q-.31 0-.52-.23T4 20.23v-4.153q0-.667.474-1.141t1.141-.474h12.77q.666 0 1.14.474T20 16.077v4.154q0 .31-.23.54t-.54.229zM6 13.462v-3.77q0-.666.475-1.14t1.14-.475H11.5V6.588q-.43-.28-.715-.638t-.285-.84q0-.3.112-.568t.334-.488L12 3l1.052 1.052q.225.225.337.491t.111.568q0 .481-.285.839q-.284.358-.715.638v1.489h3.885q.666 0 1.14.475T18 9.692v3.77z");
}

</style>
