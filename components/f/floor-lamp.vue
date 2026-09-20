<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcrjgpbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:floor-lamp" /></template>
<style>
.tcrjgpbey {
  fill: currentColor;
  d: path("M11.52 19v-8H7.115q-.413 0-.66-.333t-.118-.717l1.508-4.82q.162-.504.586-.817T9.38 4h5.277q.525 0 .949.313t.585.818L17.7 9.95q.13.385-.117.717t-.66.333h-4.404v8zm-3 2v-1h7v1z");
}

</style>
