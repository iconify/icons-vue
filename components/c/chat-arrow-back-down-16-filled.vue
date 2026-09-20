<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cs_iawdch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-arrow-back-down-16-filled" /></template>
<style>
.cs_iawdch {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 6.964 6.29a5.5 5.5 0 1 0-7.675 7.675a7 7 0 0 1-2.827-.926l-2.804.936a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m2.5 5a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m2 2a.5.5 0 0 0-.5.5v.25a1.75 1.75 0 0 1-1.75 1.75H8.707l.897-.896a.5.5 0 1 0-.708-.707l-1.751 1.752A.5.5 0 0 0 7 11c0 .136.05.258.146.354l1.75 1.75a.5.5 0 0 0 .708-.707l-.897-.897h1.543A2.75 2.75 0 0 0 13 8.75V8.5a.5.5 0 0 0-.5-.5");
}

</style>
