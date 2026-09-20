<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ojqa2p50u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-off-16-regular" /></template>
<style>
.ojqa2p50u {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707l-1.565-1.564A6.97 6.97 0 0 1 8 15c-1.29 0-2.5-.351-3.538-.96l-2.804.935a.5.5 0 0 1-.633-.633l.934-2.806A6.97 6.97 0 0 1 1 8a6.97 6.97 0 0 1 1.71-4.582L1.147 1.854a.5.5 0 0 1 0-.708M3.42 4.127A5.97 5.97 0 0 0 2 8c0 1.18.341 2.28.93 3.207a.5.5 0 0 1 .052.426l-.692 2.075l2.076-.691c.15-.033.29-.034.426.052A5.97 5.97 0 0 0 8 14a5.97 5.97 0 0 0 3.873-1.42L8.967 9.674A.5.5 0 0 1 8.5 10h-3a.5.5 0 0 1 0-1h2.793l-2-2H5.5a.5.5 0 0 1-.175-.968zM8 1a7 7 0 0 1 5.895 10.774l-.727-.727a6 6 0 0 0-8.215-8.215l-.727-.728A6.97 6.97 0 0 1 8 1m2.5 5a.5.5 0 1 1 0 1H9.121l-1-1z");
}

</style>
