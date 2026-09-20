<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g-4hxeq3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-request-16-filled" /></template>
<style>
.g-4hxeq3z {
  fill: currentColor;
  d: path("M13 10.05V5.5A2.5 2.5 0 0 0 10.5 3H8.71l1.14-1.15c.2-.19.2-.51 0-.7c-.19-.2-.51-.2-.7 0l-2 2c-.2.19-.2.51 0 .7l2 2c.19.2.51.2.7 0c.2-.19.2-.51 0-.7L8.71 4h1.79c.83 0 1.5.67 1.5 1.5v4.55a2.5 2.5 0 1 0 1 0M6 3.5a2.5 2.5 0 1 0-3 2.45v4.101c-1.14.232-2 1.242-2 2.449C1 13.879 2.122 15 3.5 15S6 13.879 6 12.5c0-1.208-.86-2.217-2-2.449V5.95A2.5 2.5 0 0 0 6 3.5");
}

</style>
