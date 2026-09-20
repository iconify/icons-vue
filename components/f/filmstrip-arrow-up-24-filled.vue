<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk6qihbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-arrow-up-24-filled" /></template>
<style>
.zk6qihbnn {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.354 2.146a.5.5 0 0 0-.707 0l-2.5 2.5a.5.5 0 1 0 .707.707L17 15.708V20.5a.5.5 0 0 0 1 0v-4.793l1.646 1.646a.5.5 0 1 0 .707-.707zM18.75 4A3.25 3.25 0 0 1 22 7.25v5.562A6.5 6.5 0 0 0 11.499 20H5.25A3.25 3.25 0 0 1 2 16.75v-9.5A3.25 3.25 0 0 1 5.25 4zm-14 11a.75.75 0 0 0-.75.75v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-.75-.75m0-4a.75.75 0 0 0-.75.75v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-.75-.75m0-4a.75.75 0 0 0-.75.75v.5a.75.75 0 0 0 1.5 0v-.5A.75.75 0 0 0 4.75 7m14.5 0a.75.75 0 0 0-.75.75v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-.75-.75");
}

</style>
