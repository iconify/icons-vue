<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um-itx_fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-overline-rounded" /></template>
<style>
.um-itx_fy {
  fill: currentColor;
  d: path("M6.192 4.5q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h11.616q.212 0 .356.144t.144.357t-.144.356t-.356.143zm1.336 13.972q-1.836-1.837-1.836-4.473T7.53 9.528T12 7.692t4.471 1.836T18.308 14t-1.836 4.472T12 20.308t-4.472-1.836m8.15-.794q1.514-1.514 1.514-3.678t-1.514-3.678T12 8.808t-3.678 1.514T6.808 14t1.514 3.678Q9.837 19.192 12 19.192t3.678-1.514");
}

</style>
