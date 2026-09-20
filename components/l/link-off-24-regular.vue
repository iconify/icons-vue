<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8l8lrbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-off-24-regular" /></template>
<style>
.t8l8lrbpa {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06L15.94 17h-1.19a.75.75 0 0 1-.262-1.451L11.69 12.75H7a.75.75 0 0 1-.102-1.493L7 11.25h3.19L7.44 8.5H7a3.5 3.5 0 0 0-.206 6.994L7 15.5h2.25a.75.75 0 0 1 .11 1.492L9.25 17H7a5 5 0 0 1-.968-9.907L2.22 3.28a.75.75 0 0 1 0-1.06M17 7a5 5 0 0 1 2.507 9.325l-1.114-1.114a3.5 3.5 0 0 0-1.187-6.705L17 8.5h-2.25a.75.75 0 0 1-.11-1.492L14.75 7zm0 4.25a.75.75 0 0 1 .102 1.493L17 12.75h-1.068l-1.5-1.5z");
}

</style>
