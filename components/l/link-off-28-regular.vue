<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kpffqobkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-off-28-regular" /></template>
<style>
.kpffqobkm {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06L18.94 20H17a.75.75 0 0 1-.102-1.493L17 18.5h.44l-3.75-3.75H8a.75.75 0 0 1-.102-1.493L8 13.25h4.19L8.44 9.5H8a4.5 4.5 0 0 0-.212 8.995L8 18.5h3a.75.75 0 0 1 .102 1.493L11 20H8a6 6 0 0 1-.98-11.92l-4.8-4.8a.75.75 0 0 1 0-1.06M20 8a6 6 0 0 1 2.593 11.41l-1.15-1.15a4.5 4.5 0 0 0-1.231-8.755L20 9.5h-3a.75.75 0 0 1-.102-1.493L17 8zm0 5.25a.75.75 0 0 1 .102 1.493L20 14.75h-2.067l-1.5-1.5z");
}

</style>
