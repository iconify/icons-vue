<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lp3qwdfxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-postscript" /></template>
<style>
.lp3qwdfxz {
  fill: var(--svg-color--cc2131, #cc2131);
  d: path("M18.2 3.1c.77.21 1.2.39 1.7.76l-9.3 11c2.5 1.7 5.2 5.9 3.7 9.4c.72-4.7-4-8.2-6.8-8.6zm-7.4 26c1.7.08 3.5.1 5.2.1c3.9 0 7.6-.18 11-.52a2.9 2.9 0 0 0 2.5-2.5q.44-3.6.43-7.5a51 51 0 0 0-.42-7.5a2.74 2.74 0 0 0-2.5-2.5c-1.6-.16-3.1-.29-4.7-.37c0 0-6.7 15-7.3 16c-1 2.3-2.4 3.9-4.3 4.5zm-5.9-.42c-1.3-.24-2.3-.99-2.5-2.5q-.38-3.6-.38-7.5c0-3.9.13-5.1.39-7.5c.18-1.4 1.2-2.4 2.5-2.5c1.8-.18 3.7-.31 5.6-.42l3.4-3.9c-.03 0 .79-.16 1.5.03l-12 14c2.6-1.3 10 .7 10 5.3c0 4.9-5.2 5.4-8.7 4.9z");
}

</style>
