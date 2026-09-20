<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f-kwhccwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:expand-up-left-28-filled" /></template>
<style>
.f-kwhccwo {
  fill: currentColor;
  d: path("M21.25 4.5a2.25 2.25 0 0 1 2.25 2.25V14h-6.75A2.75 2.75 0 0 0 14 16.75v6.75H6.75a2.25 2.25 0 0 1-2.25-2.25v-5a.75.75 0 0 0-1.5 0v5A3.75 3.75 0 0 0 6.75 25h14.5A3.75 3.75 0 0 0 25 21.25V6.75A3.75 3.75 0 0 0 21.25 3h-5a.75.75 0 0 0 0 1.5zm-8.75-.75a.75.75 0 0 0-.75-.75h-8a.75.75 0 0 0-.75.75v8a.75.75 0 0 0 1.5 0V5.56l6.22 6.22a.75.75 0 1 0 1.06-1.06L5.56 4.5h6.19a.75.75 0 0 0 .75-.75");
}

</style>
