<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zujbuibyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:case-pack" /></template>
<style>
.zujbuibyv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.75 10.25h.5V5q0-1.75 1.75-1.75h2q1.75 0 1.75 1.75v5.25h.5V5q0-1.75 1.75-1.75h2q1.75 0 1.75 1.75v5.625q1.5.75 1.5 3v4.25q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375v-4.25q0-2.25 1.5-3V5q0-1.75 1.75-1.75h2q1.75 0 1.75 1.75zm10.5.011V5q0-.25-.25-.25h-2q-.25 0-.25.25v5.25h2.125q.193 0 .375.011m-14.5 0q.182-.011.375-.011H7.25V5q0-.25-.25-.25H5q-.25 0-.25.25zm8.5-.011h-2.5V5q0-.25.25-.25h2q.25 0 .25.25z");
}

</style>
