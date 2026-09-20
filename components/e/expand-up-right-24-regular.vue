<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7issbbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:expand-up-right-24-regular" /></template>
<style>
.h7issbbmj {
  fill: currentColor;
  d: path("M4.5 6.25c0-.966.784-1.75 1.75-1.75h4a.75.75 0 0 0 0-1.5h-4A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75v-4a.75.75 0 0 0-1.5 0v4a1.75 1.75 0 0 1-1.75 1.75H12v-4.75A2.75 2.75 0 0 0 9.25 12H4.5zm0 7.25h4.75c.69 0 1.25.56 1.25 1.25v4.75H6.25a1.75 1.75 0 0 1-1.75-1.75zM13 3.75a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0V5.56l-5.22 5.22a.75.75 0 0 1-1.06-1.06l5.22-5.22h-4.69a.75.75 0 0 1-.75-.75");
}

</style>
