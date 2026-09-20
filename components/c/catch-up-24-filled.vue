<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps7iwtxjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:catch-up-24-filled" /></template>
<style>
.ps7iwtxjy {
  fill: currentColor;
  d: path("M11.372 7.269c-.666-1.701-3.076-1.692-3.73.013l-1.207 3.149a.5.5 0 0 1-.466.32H4.562a2 2 0 1 0 .292 2H5.97a2.5 2.5 0 0 0 2.334-1.605L9.51 7.998l3.22 8.227c.638 1.628 2.91 1.712 3.666.136l1.597-3.326a.5.5 0 0 1 .45-.283h.703a2 2 0 1 0 .292-2h-.994a2.5 2.5 0 0 0-2.254 1.418l-1.597 3.326z");
}

</style>
