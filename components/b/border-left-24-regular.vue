<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq0k6r8yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:border-left-24-regular" /></template>
<style>
.iq0k6r8yo {
  fill: currentColor;
  d: path("M6.25 3a.75.75 0 0 1 0 1.5h-.5c-.69 0-1.25.56-1.25 1.25v12.5c0 .69.56 1.25 1.25 1.25h.5a.75.75 0 0 1 0 1.5h-.5A2.75 2.75 0 0 1 3 18.25V5.75A2.75 2.75 0 0 1 5.75 3zm7 1.5a.75.75 0 0 0 0-1.5h-2.5a.75.75 0 0 0 0 1.5zm6.25 6.25a.75.75 0 0 1 1.5 0v2.5a.75.75 0 0 1-1.5 0zm-5.5 9.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1 0-1.5h2.5a.75.75 0 0 1 .75.75M17.75 3a.75.75 0 0 0 0 1.5h.5c.69 0 1.25.56 1.25 1.25v.5a.75.75 0 0 0 1.5 0v-.5A2.75 2.75 0 0 0 18.25 3zM17 20.25c0 .414.336.75.75.75h.5A2.75 2.75 0 0 0 21 18.25v-.5a.75.75 0 0 0-1.5 0v.5c0 .69-.56 1.25-1.25 1.25h-.5a.75.75 0 0 0-.75.75");
}

</style>
