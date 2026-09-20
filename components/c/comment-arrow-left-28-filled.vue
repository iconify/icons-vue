<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dbmoajbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-arrow-left-28-filled" /></template>
<style>
.dbmoajbgo {
  fill: currentColor;
  d: path("M20.5 14a6.5 6.5 0 1 1 0-13a6.5 6.5 0 0 1 0 13m4-6a.5.5 0 0 0 0-1h-6.793l2.147-2.146a.5.5 0 0 0-.708-.708l-3 3a.5.5 0 0 0-.146.351v.006c0 .127.05.254.146.35l3 3a.5.5 0 0 0 .708-.707L17.707 8zm-4 7a7.48 7.48 0 0 0 5.5-2.4v4.65A3.75 3.75 0 0 1 22.25 21h-5.941l-6.535 4.715C8.616 26.55 7 25.723 7 24.295V21H5.75A3.75 3.75 0 0 1 2 17.25V6.75A3.75 3.75 0 0 1 5.75 3h8.75a7.5 7.5 0 0 0 6 12");
}

</style>
