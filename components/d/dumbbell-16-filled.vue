<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p3wlxn96k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dumbbell-16-filled" /></template>
<style>
.p3wlxn96k {
  fill: currentColor;
  d: path("M11.752 2.043a1.72 1.72 0 0 0-2.6.195A2.088 2.088 0 0 0 7.308 5.77l.876.876l-.831.832l1.183 1.184l.832-.832l.877.877a2.088 2.088 0 0 0 3.532-1.843a1.72 1.72 0 0 0 .195-2.6l-.519-.519l.454-.454a.837.837 0 0 0-1.183-1.184l-.454.454zm.282 3.733a.5.5 0 0 1-.708 0l-1.103-1.103a.5.5 0 0 1 .707-.707l1.104 1.103a.5.5 0 0 1 0 .707M2.817 7.31a2.09 2.09 0 0 1 2.953 0l2.937 2.937a2.088 2.088 0 0 1-1.843 3.531a1.72 1.72 0 0 1-2.6.195l-.519-.518l-.469.47a.837.837 0 1 1-1.184-1.184l.47-.47l-.52-.518a1.72 1.72 0 0 1 .196-2.6a2.09 2.09 0 0 1 .58-1.843m2.598 4.379l-1.103-1.103a.5.5 0 0 0-.707.707l1.103 1.103a.5.5 0 0 0 .707-.707");
}

</style>
