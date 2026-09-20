<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hze7kcp-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-fit-in-24-filled" /></template>
<style>
.hze7kcp-o {
  fill: currentColor;
  d: path("M5.818 7.519a1 1 0 0 0-.05 1.413L7.699 11H3a1 1 0 1 0 0 2h4.699l-1.93 2.068a1 1 0 0 0 1.462 1.364l3.498-3.747a1 1 0 0 0 .149-.205a1 1 0 0 0-.148-1.163l-3.499-3.75a1 1 0 0 0-1.413-.048m12.364 0a1 1 0 0 1 .05 1.413L16.301 11H21a1 1 0 1 1 0 2h-4.699l1.93 2.068a1 1 0 0 1-1.462 1.364l-3.498-3.747a1 1 0 0 1-.149-.205a1 1 0 0 1 .148-1.164l3.499-3.748a1 1 0 0 1 1.413-.049");
}

</style>
