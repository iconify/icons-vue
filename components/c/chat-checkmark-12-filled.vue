<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ryxvx_h1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-checkmark-12-filled" /></template>
<style>
.ryxvx_h1s {
  fill: currentColor;
  d: path("M6 1a5 5 0 1 1-2.41 9.382l-1.945.593a.5.5 0 0 1-.624-.624l.593-1.948A5 5 0 0 1 6 1m2.354 3.396a.5.5 0 0 0-.708 0L5.5 6.543L4.354 5.396a.5.5 0 0 0-.708.708l1.5 1.5a.5.5 0 0 0 .708 0l2.5-2.5a.5.5 0 0 0 0-.708");
}

</style>
