<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjjybzdzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:done-all-outline" /></template>
<style>
.pjjybzdzp {
  fill: currentColor;
  d: path("m6.7 18l-5.65-5.65l1.425-1.4l4.25 4.25l1.4 1.4zm5.65 0L6.7 12.35l1.4-1.425l4.25 4.25l9.2-9.2l1.4 1.425zm0-5.65l-1.425-1.4L15.875 6L17.3 7.4z");
}

</style>
