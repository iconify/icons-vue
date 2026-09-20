<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em2s0abcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comment-outline" /></template>
<style>
.em2s0abcm {
  fill: currentColor;
  d: path("M6.5 13.5h11v-1h-11zm0-3h11v-1h-11zm0-3h11v-1h-11zM21 20.077L17.923 17H4.616q-.691 0-1.154-.462T3 15.385V4.615q0-.69.463-1.153T4.615 3h14.77q.69 0 1.152.462T21 4.615zM4.616 16H18.35L20 17.644V4.616q0-.231-.192-.424T19.385 4H4.615q-.23 0-.423.192T4 4.615v10.77q0 .23.192.423t.423.192M4 16V4z");
}

</style>
