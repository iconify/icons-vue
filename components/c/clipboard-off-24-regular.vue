<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfoc0gbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-off-24-regular" /></template>
<style>
.jfoc0gbrl {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06l-.982-.981A2.25 2.25 0 0 1 17.75 22H6.25A2.25 2.25 0 0 1 4 19.75V6.25c0-.347.08-.675.22-.969l-2-2a.75.75 0 0 1 0-1.061M5.5 19.75c0 .414.336.75.75.75h11.5a.75.75 0 0 0 .75-.75v-.19l-13-13zM13.75 2a2.25 2.25 0 0 1 2.236 2h1.764A2.25 2.25 0 0 1 20 6.25v10.568l-1.5-1.5V6.25a.75.75 0 0 0-.75-.75h-2.129c-.404.603-1.091 1-1.871 1h-3.5q-.352-.001-.67-.103L7.181 4h.832a2.25 2.25 0 0 1 2.236-2zm-3.5 1.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5z");
}

</style>
