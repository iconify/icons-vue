<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xezk3371h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-style-guide-20-regular" /></template>
<style>
.xezk3371h {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-3h1v3c0 .373.102.722.28 1.02l4.668-4.588a1.5 1.5 0 0 1 2.104 0l4.669 4.589c.177-.299.279-.648.279-1.02V6a2 2 0 0 0-2-2h-3.107l.02-.074c.082-.311.101-.625.067-.927zm-3.65 8.146a.5.5 0 0 0-.7 0l-4.662 4.58C5.285 15.9 5.631 16 6 16h8c.37 0 .715-.1 1.012-.274zM5.5 3A1.5 1.5 0 0 1 7 4.5v4A1.5 1.5 0 0 1 5.5 10h-3A1.5 1.5 0 0 1 1 8.5v-4A1.5 1.5 0 0 1 2.5 3zm7 3a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3M4.187 2a1.5 1.5 0 0 1 1.8-.946l2.898.776a1.5 1.5 0 0 1 1.06 1.838L8.91 7.532c-.13.482-.48.844-.914 1.01L8 8.5v-4a2.47 2.47 0 0 0-.365-1.297A2.5 2.5 0 0 0 5.499 2zM12.5 7a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1");
}

</style>
