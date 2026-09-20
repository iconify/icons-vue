<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lny2phbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edit-audio-outline" /></template>
<style>
.lny2phbem {
  fill: currentColor;
  d: path("M6.192 21L3 17.827l3.192-3.173l.714.688l-2.004 1.985h14.157l-1.978-1.985l.707-.688L21 17.827L17.788 21l-.713-.688l2.004-1.985H4.92l1.98 1.985zm5.308-8.365V2.096h1v10.539zM7.75 10.73V4h1v6.73zm7.5 0V4h1v6.73zM4 8.346V6.423h1v1.923zm15 0V6.423h1v1.923z");
}

</style>
