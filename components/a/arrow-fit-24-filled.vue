<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js4bkxbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-fit-24-filled" /></template>
<style>
.js4bkxbqr {
  fill: currentColor;
  d: path("M7.182 7.519a1 1 0 0 1 .05 1.413L5.301 11H10a1 1 0 1 1 0 2H5.301l1.93 2.068a1 1 0 0 1-1.462 1.364L2.27 12.685A1 1 0 0 1 2 12a1 1 0 0 1 .27-.684l3.5-3.748a1 1 0 0 1 1.413-.049m9.636 0a1 1 0 0 0-.05 1.413L18.699 11H14a1 1 0 1 0 0 2h4.699l-1.93 2.068a1 1 0 0 0 1.462 1.364l3.498-3.747a1 1 0 0 0 .149-.205a1 1 0 0 0-.148-1.163l-3.499-3.75a1 1 0 0 0-1.413-.048");
}

</style>
