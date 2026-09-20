<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xhs_13u4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-arrow-left-28-regular" /></template>
<style>
.xhs_13u4i {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0-13a6.5 6.5 0 0 1 0 13m4-6a.5.5 0 0 0 0-1h-6.793l2.147-2.146a.5.5 0 0 0-.708-.708l-3 3a.5.5 0 0 0-.146.351v.006c0 .127.05.254.146.35l3 3a.5.5 0 0 0 .708-.707L17.707 8zm0 9.25v-3.405A7.5 7.5 0 0 0 26 12.6v4.651A3.75 3.75 0 0 1 22.25 21h-5.941l-6.535 4.715C8.616 26.55 7 25.723 7 24.295V21H5.75A3.75 3.75 0 0 1 2 17.25V6.75A3.75 3.75 0 0 1 5.75 3h8.75a7.5 7.5 0 0 0-.876 1.5H5.75A2.25 2.25 0 0 0 3.5 6.75v10.5a2.25 2.25 0 0 0 2.25 2.25H8.5v4.796c0 .203.23.322.396.202l6.928-4.998h6.426a2.25 2.25 0 0 0 2.25-2.25");
}

</style>
