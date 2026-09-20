<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i4nr2086m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:form-new-32-regular" /></template>
<style>
.i4nr2086m {
  fill: currentColor;
  d: path("M23 15.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M24.5 3A4.5 4.5 0 0 1 29 7.5v8.793a9 9 0 0 0-2-1.355V7.5A2.5 2.5 0 0 0 24.5 5h-17A2.5 2.5 0 0 0 5 7.5v17A2.5 2.5 0 0 0 7.5 27h7.438c.361.728.818 1.4 1.355 2H7.5A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-1.25 14.5a.75.75 0 0 0-.75.75V22h-3.75a.75.75 0 0 0 0 1.5h3.75v3.75a.75.75 0 0 0 1.5 0V23.5h3.75a.75.75 0 0 0 0-1.5H24v-3.75a.75.75 0 0 0-.75-.75M10 19a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 2a1 1 0 1 0 0 2a1 1 0 0 0 0-2m0-10a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0 2a1 1 0 1 0 0 2a1 1 0 0 0 0-2m14 0a1 1 0 0 1 .975 1.22A9 9 0 0 0 23 14a8.96 8.96 0 0 0-4.122 1H16a1 1 0 1 1 0-2zm0-6a1 1 0 1 1 0 2H8a1 1 0 0 1 0-2z");
}

</style>
