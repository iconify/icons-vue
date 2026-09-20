<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saj25_7qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flashlight-24-filled" /></template>
<style>
.saj25_7qt {
  fill: currentColor;
  d: path("M16.75 1.25a.75.75 0 0 1 .75.75v1A.75.75 0 0 1 16 3V2a.75.75 0 0 1 .75-.75m3.72 1.22a.75.75 0 0 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06-1.06zM8.25 6.31v2.88l6.56 6.56h2.879zM19.06 15l1.41-1.409a2.25 2.25 0 0 0 0-3.182L13.59 3.53a2.25 2.25 0 0 0-3.181 0l-1.41 1.41zM13 16.06L7.94 11l-4.91 4.909a2.25 2.25 0 0 0 0 3.182l1.88 1.879a2.25 2.25 0 0 0 3.182 0zm-3.47-1.59a.75.75 0 0 1 0 1.06l-1.5 1.5a.75.75 0 1 1-1.06-1.06l1.5-1.5a.75.75 0 0 1 1.06 0M22 8h-1a.75.75 0 0 1 0-1.5h1A.75.75 0 0 1 22 8");
}

</style>
