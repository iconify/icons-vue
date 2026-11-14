<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgvnl_e6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ct-scan-slice" /></template>
<style>
.pgvnl_e6u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-3.47 3.068-5.892Q7.805 3.75 12 3.75t7.182 2.358Q22.25 8.53 22.25 12t-3.068 5.892Q16.195 20.25 12 20.25t-7.182-2.358Q1.75 15.47 1.75 12m8.147-5.235q-.039-.008-.079-.012q-2.42-.22-3.984 1.228Q4.25 9.448 4.25 12q0 2.526 1.419 3.885q1.395 1.337 3.656 1.111q.036-.003.072-.011q1.32-.263 1.721-1.467q.342-1.026-.197-2.103q-.702-1.403-.012-2.806q.711-1.198.585-2.202q-.169-1.357-1.597-1.642m4.285-.012q-.04.004-.079.012q-1.428.285-1.597 1.642q-.126 1.004.585 2.202q.69 1.403-.012 2.806q-.539 1.077-.197 2.103q.401 1.204 1.721 1.467q.036.008.072.011q2.261.226 3.656-1.111Q19.75 14.526 19.75 12q0-2.552-1.584-4.019q-1.564-1.448-3.984-1.228");
}

</style>
