<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xt0zdyb2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:edit-off-12-regular" /></template>
<style>
.xt0zdyb2d {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .707 0l9 9a.5.5 0 0 1-.707.707L7.002 7.71l-2.645 2.645a.5.5 0 0 1-.255.136l-2.504.5a.5.5 0 0 1-.588-.589l.504-2.5a.5.5 0 0 1 .136-.255l2.645-2.644l-3.149-3.148a.5.5 0 0 1 0-.708m1.318 7.101l-.325 1.615l1.619-.323l2.537-2.537L5.002 5.71zm5.272-6.686a1.914 1.914 0 0 1 2.707 2.707L8.416 6.295l-.707-.707l1.086-1.086l-1.293-1.293l-1.086 1.086l-.707-.707L7.11 2.186a.5.5 0 0 1 .075-.075zm2 .707a.915.915 0 0 0-1.293 0l-.234.234l1.293 1.293l.234-.234a.915.915 0 0 0 0-1.293");
}

</style>
