<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s3t23s65d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-left-outline" /></template>
<style>
.s3t23s65d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.4881 4.43056C15.8026 4.70012 15.839 5.1736 15.5694 5.48809L9.98781 12L15.5694 18.5119C15.839 18.8264 15.8026 19.2999 15.4881 19.5694C15.1736 19.839 14.7001 19.8026 14.4306 19.4881L8.43056 12.4881C8.18981 12.2072 8.18981 11.7928 8.43056 11.5119L14.4306 4.5119C14.7001 4.19741 15.1736 4.16099 15.4881 4.43056Z");
}

</style>
