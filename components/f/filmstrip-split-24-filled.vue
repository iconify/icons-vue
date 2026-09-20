<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_ztxb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filmstrip-split-24-filled" /></template>
<style>
.pv_ztxb2y {
  fill: currentColor;
  d: path("M12.75 2.75a.75.75 0 0 0-1.5 0v18.5a.75.75 0 0 0 1.5 0zM2 7.25A3.25 3.25 0 0 1 5.25 4h5v16h-5A3.25 3.25 0 0 1 2 16.75zM4.75 7a.75.75 0 0 0-.75.75v.5a.75.75 0 0 0 1.5 0v-.5A.75.75 0 0 0 4.75 7M4 15.75v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-1.5 0M4.75 11a.75.75 0 0 0-.75.75v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-.75-.75m9 9V4h5A3.25 3.25 0 0 1 22 7.25v9.5A3.25 3.25 0 0 1 18.75 20zM18.5 7.75v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-1.5 0m.75 7.25a.75.75 0 0 0-.75.75v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-.75-.75m-.75-3.25v.5a.75.75 0 0 0 1.5 0v-.5a.75.75 0 0 0-1.5 0");
}

</style>
