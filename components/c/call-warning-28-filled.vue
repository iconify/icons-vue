<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="g5xe-ibus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-warning-28-filled" /></template>
<style>
.g5xe-ibus {
  fill: currentColor;
  d: path("M4.09 2.881c1.12-.719 2.552-.995 3.967-.802l.246.034a2.75 2.75 0 0 1 2.088 1.495l1.291 2.582a3.25 3.25 0 0 1-1.104 4.157L8.87 11.486c-.397.264-.508.631-.42.899c.53 1.614 1.94 3.802 3.169 5.055c.23.235.648.306 1.076.07l1.304-.718a3.75 3.75 0 0 1 5.1 1.49l1.041 1.912a2.75 2.75 0 0 1 .014 2.608c-1.45 2.726-4.757 4.239-7.563 2.402c-2.394-1.566-5.336-4.162-7.743-8.33c-2.442-4.23-2.93-7.896-2.78-10.55c.087-1.532.886-2.714 2.022-3.443m14.074-1.054c.552-1.103 2.12-1.103 2.673 0l5.002 9.993c.5 1-.224 2.18-1.337 2.18H14.498c-1.114 0-1.837-1.18-1.336-2.18zM19.5 11a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m0-7a.5.5 0 0 0-.5.5v5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.5-.5");
}

</style>
