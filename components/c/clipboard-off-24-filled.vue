<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9reoch3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-off-24-filled" /></template>
<style>
.w9reoch3q {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-.982-.981A2.25 2.25 0 0 1 17.75 22H6.25A2.25 2.25 0 0 1 4 19.75V6.25c0-.347.08-.675.22-.969l-2-2a.75.75 0 0 1 0-1.061M13.75 2a2.25 2.25 0 0 1 2.236 2h1.764A2.25 2.25 0 0 1 20 6.25v10.568L7.182 4h.832a2.25 2.25 0 0 1 2.236-2zm-3.5 1.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5z");
}

</style>
