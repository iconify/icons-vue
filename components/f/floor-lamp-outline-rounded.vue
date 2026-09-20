<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q91zike4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:floor-lamp-outline-rounded" /></template>
<style>
.q91zike4x {
  fill: currentColor;
  d: path("M11.663 18.856q-.144-.144-.144-.356V11H7.116q-.413 0-.66-.333t-.118-.717l1.508-4.82q.162-.504.586-.817T9.38 4h5.277q.525 0 .949.313t.585.818L17.7 9.95q.13.385-.117.717t-.66.333h-4.404v7.5q0 .213-.144.356T12.02 19t-.356-.144M7.369 10h9.3l-1.415-4.558q-.058-.192-.221-.317T14.658 5H9.38q-.212 0-.375.125t-.221.317zm1.65 11q-.212 0-.356-.144t-.144-.357t.144-.356t.356-.143h6q.213 0 .356.144t.144.357t-.144.356t-.356.143zm3-13.5");
}

</style>
