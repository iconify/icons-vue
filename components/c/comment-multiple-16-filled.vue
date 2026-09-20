<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c0sfd9r7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-multiple-16-filled" /></template>
<style>
.c0sfd9r7m {
  fill: currentColor;
  d: path("M14 10.732V6a3 3 0 0 0-3-3H3.268A2 2 0 0 1 5 2h6a4 4 0 0 1 4 4v3a2 2 0 0 1-1 1.732M1 6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H7.073l-2.485 1.807A1 1 0 0 1 3 13.998V13a2 2 0 0 1-2-2z");
}

</style>
