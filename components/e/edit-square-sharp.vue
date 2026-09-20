<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c18zc5bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-square-sharp" /></template>
<style>
.c18zc5bnx {
  fill: currentColor;
  d: path("M9 15v-4.25L19.625.125L23.8 4.4L13.25 15zm10.6-9.2l1.425-1.4l-1.4-1.4L18.2 4.4zM3 21V3h10.925L7 9.925V17h7.05L21 10.05V21z");
}

</style>
