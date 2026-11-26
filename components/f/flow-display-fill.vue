<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kyt6z1box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flow-display-fill" /></template>
<style>
.kyt6z1box {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.6569 6.3431C22.1035 7.7898 23 9.7911 23 12C23 16.4183 19.4183 20 15 20L8.886 20C8.0397 20 7.2327 19.6426 6.664 19.0157L1.5187 13.3438C0.8271 12.5814 0.8271 11.4186 1.5186 10.6562L6.6641 4.9843C7.2327 4.3574 8.0397 4 8.886 4L15 4C17.2089 4 19.2102 4.8965 20.6569 6.3431Z");
}

</style>
