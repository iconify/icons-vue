<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzptj1b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-selection-sharp" /></template>
<style>
.lzptj1b4l {
  fill: currentColor;
  d: path("M11 21V11h10v2h-6.6l6.6 6.6l-1.4 1.4l-6.6-6.6V21zm-4 0v-2h2v2zM3 5V3h2v2zm4 0V3h2v2zm4 0V3h2v2zm4 0V3h2v2zm4 0V3h2v2zM3 21v-2h2v2zm0-4v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zm16 0V7h2v2z");
}

</style>
