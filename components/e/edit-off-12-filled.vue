<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="vn6n8wbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:edit-off-12-filled" /></template>
<style>
.vn6n8wbee {
  fill: currentColor;
  d: path("M1.147 1.146a.5.5 0 0 1 .707 0l9 9a.5.5 0 0 1-.707.707L7.002 7.71l-2.645 2.645a.5.5 0 0 1-.255.136l-2.504.5a.5.5 0 0 1-.588-.589l.504-2.5a.5.5 0 0 1 .136-.255l2.645-2.644l-3.148-3.148a.5.5 0 0 1 0-.708M9.502 5.21L8.416 6.295L5.709 3.588l1.086-1.086zM7.736 1.561a1.914 1.914 0 0 1 2.707 2.707l-.234.234l-2.707-2.707z");
}

</style>
