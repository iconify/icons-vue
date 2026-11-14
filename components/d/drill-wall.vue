<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdc564bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drill-wall" /></template>
<style>
.zdc564bzz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 2.25h.5q2.25 0 2.25 2.25v15q0 2.25-2.25 2.25h-.5q-2.25 0-2.25-2.25v-10h-2.532q-.296 2.75-3.343 2.75H9.933l-.686 7.32q-.007.069-.026.136t-.05.129t-.073.117q-.042.056-.093.103t-.11.083t-.124.061t-.133.038t-.138.013h-4q-.047 0-.093-.006q-.073-.009-.143-.032q-.071-.024-.135-.06q-.064-.037-.12-.085t-.101-.107t-.078-.124t-.053-.137t-.025-.145t.004-.147l.911-7.287q-.798-.228-1.428-.859q-.989-.988-.989-2.386v-.25q0-3.375 3.375-3.375h5.75q3.047 0 3.343 2.75h2.532V4.5q0-2.25 2.25-2.25M5.35 18.75h2.467l.609-6.5H6.162z");
}

</style>
