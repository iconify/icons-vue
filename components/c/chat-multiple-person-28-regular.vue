<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g3j6y2wyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-multiple-person-28-regular" /></template>
<style>
.g3j6y2wyz {
  fill: currentColor;
  d: path("M19.926 7.486a9.004 9.004 0 0 1 5.122 12.546l.908 3.389a1.25 1.25 0 0 1-1.531 1.531l-3.386-.907A9 9 0 0 1 17 25a8.98 8.98 0 0 1-6.731-3.026a10 10 0 0 0 2.108-.068A7.47 7.47 0 0 0 17 23.5a7.46 7.46 0 0 0 3.59-.914a.75.75 0 0 1 .555-.066l3.25.87l-.872-3.251a.75.75 0 0 1 .067-.554c.58-1.064.91-2.285.91-3.585a7.5 7.5 0 0 0-3.825-6.54a10 10 0 0 0-.75-1.974M11 3a9 9 0 1 1-4.04 17.045l-3.385.907a1.25 1.25 0 0 1-1.531-1.531l.908-3.389A9 9 0 0 1 11 3m0 1.5a7.5 7.5 0 0 0-6.59 11.085a.75.75 0 0 1 .067.554l-.873 3.252l3.251-.871a.75.75 0 0 1 .554.066A7.5 7.5 0 1 0 11 4.5m2.75 8.5c.966 0 1.75.784 1.75 1.75c0 1.75-2 3.25-4.5 3.25s-4.5-1.5-4.5-3.25c0-.966.784-1.75 1.75-1.75zM11 6.5a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
