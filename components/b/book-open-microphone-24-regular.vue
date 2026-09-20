<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj8f3sbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-24-regular" /></template>
<style>
.tj8f3sbya {
  fill: currentColor;
  d: path("M22.25 16a.75.75 0 0 1 .75.75a4.75 4.75 0 0 1-4 4.69v.81a.75.75 0 0 1-1.5 0v-.81a4.75 4.75 0 0 1-4-4.69a.75.75 0 0 1 1.5 0a3.25 3.25 0 0 0 6.5 0a.75.75 0 0 1 .75-.75M10 4c.788 0 1.499.331 2 .862A2.74 2.74 0 0 1 14 4h6.25c.966 0 1.75.784 1.75 1.75v9.27a1.8 1.8 0 0 0-.5.15v-.92c0-.92-.385-1.75-1-2.342V5.75a.25.25 0 0 0-.25-.25H14c-.69 0-1.25.56-1.25 1.25v9.102a1.74 1.74 0 0 0-.25.898a5.7 5.7 0 0 0 .97 3.196a2.74 2.74 0 0 1-1.47-.808A2.74 2.74 0 0 1 10 20H3.75A1.75 1.75 0 0 1 2 18.25V5.75C2 4.784 2.784 4 3.75 4zm8.25 8a2.25 2.25 0 0 1 2.25 2.25v2.5a2.25 2.25 0 0 1-4.5 0v-2.5A2.25 2.25 0 0 1 18.25 12M3.75 5.5a.25.25 0 0 0-.25.25v12.5c0 .138.112.25.25.25H10c.69 0 1.25-.56 1.25-1.25V6.75c0-.69-.56-1.25-1.25-1.25z");
}

</style>
