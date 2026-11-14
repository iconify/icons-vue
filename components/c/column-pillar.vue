<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnt3x2b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:column-pillar" /></template>
<style>
.nnt3x2b1f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.51 1.75h8.98q1.306.002 1.77 1.222t-.511 2.088l-1.825 1.622q-.085.075-.174.141v8.914l1.61 2.013H18q2.25 0 2.25 2.25T18 22.25H6q-2.25 0-2.25-2.25T6 17.75h.64l1.61-2.013V6.823q-.089-.066-.174-.141L6.252 5.061q-.975-.869-.512-2.089q.464-1.22 1.769-1.222zm6.904 14.719l1.026 1.281H8.56l1.026-1.281q.079-.1.122-.221q.042-.12.042-.248V7.25h4.5V16q0 .128.042.248q.043.121.122.221");
}

</style>
