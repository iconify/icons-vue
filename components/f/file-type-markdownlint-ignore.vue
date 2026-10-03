<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x3niikb1r"/><path class="neg96x8kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-markdownlint-ignore" /></template>
<style>
.neg96x8kq {
  fill: var(--svg-color--755838, #755838);
  d: path("M5.5 17.75h1.75v7H9v1.75H5.5zm5.25 0h1.75v1.75h-1.75zm0 3.5h1.75v5.25h-1.75zm3.5 0h5.25v5.25h-1.75V23H16v3.5h-1.75zM23 18.63h1.75v2.62h1.75V23h-1.75v3.5H23V23h-1.75v-1.75H23z");
}

.x3niikb1r {
  fill: var(--svg-color--96231e, #96231e);
  d: path("M4.05 2h23.9A3.4 3.4 0 0 1 30 4.05v23.9A3.4 3.4 0 0 1 27.95 30H4.05A3.4 3.4 0 0 1 2 27.95V4.05A3.4 3.4 0 0 1 4.05 2m.8 1.75a1.1 1.1 0 0 0-1.1 1.1v22.3a1.1 1.1 0 0 0 1.1 1.1h22.3a1.1 1.1 0 0 0 1.1-1.1V4.85a1.1 1.1 0 0 0-1.1-1.1zM19.5 5.5H23v5.25h3.8l-5.55 5.55l-5.55-5.55h3.8zm-14 1.95c-.07-.68.72-1.35 1.33-.9c1.09.9 1.99 2.01 3.05 2.95c1-.9 1.9-1.95 2.91-2.85c.5-.52 1.45-.12 1.44.6c.04 2.9 0 5.83.02 8.75H12.5q.02-3.3-.01-6.6c-.74.66-1.37 1.43-2.12 2.06a.84.84 0 0 1-1.11-.1c-.7-.62-1.3-1.33-2-1.95c-.03 2.2 0 4.4-.01 6.59H5.5z");
}

</style>
