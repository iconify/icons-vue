<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xhwrj2muc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-multiple-person-20-filled" /></template>
<style>
.xhwrj2muc {
  fill: currentColor;
  d: path("M15.802 6.627a6.48 6.48 0 0 1 2.199 4.873c0 1.151-.3 2.233-.826 3.172l.796 2.082a1 1 0 0 1-1.204 1.32l-2.487-.697A6.5 6.5 0 0 1 11.5 18a6.49 6.49 0 0 1-4.926-2.26a7.5 7.5 0 0 0 1.76.257A5.5 5.5 0 0 0 11.5 17c.902 0 1.752-.217 2.502-.6l.174-.09l2.86.801l-.969-2.536l.128-.21c.51-.834.805-1.814.805-2.865a5.47 5.47 0 0 0-.964-3.11a7.5 7.5 0 0 0-.235-1.763M8.538 2a6.5 6.5 0 1 1-2.78 12.377l-2.487.697a1 1 0 0 1-1.203-1.32l.795-2.082A6.5 6.5 0 0 1 8.538 2M6.75 9c-.69 0-1.25.56-1.25 1.25c0 1.25 1 2.25 3 2.25s3-1 3-2.25c0-.69-.56-1.25-1.25-1.25zM8.5 4.5a1.75 1.75 0 1 0 0 3.501a1.75 1.75 0 0 0 0-3.501");
}

</style>
