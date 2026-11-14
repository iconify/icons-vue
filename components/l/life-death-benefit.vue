<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0lcfjbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:life-death-benefit" /></template>
<style>
.v0lcfjbrc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.125 11.75L6.233 8.043q-.07-.066-.121-.148q-2.018-3.263 1.244-5.282Q10.125.899 12 2.992q1.875-2.093 4.644-.379q3.262 2.019 1.244 5.282q-.051.082-.121.148l-3.892 3.707h5q3.375 0 3.375 3.375v3.75q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375v-3.75q0-1.398.989-2.386q.988-.989 2.386-.989zM9.75 17q0 2.25 2.25 2.25T14.25 17T12 14.75T9.75 17");
}

</style>
