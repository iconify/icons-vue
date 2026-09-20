<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhdr_oo-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-merge-sharp" /></template>
<style>
.qhdr_oo-g {
  fill: currentColor;
  d: path("m7.016 19l-.708-.708L11.5 13.1V5.952L8.406 9.046l-.714-.713L12 4.025l4.314 4.314l-.714.713l-3.1-3.1v7.564zm9.969.006L13.4 15.427l.714-.713l3.578 3.584z");
}

</style>
