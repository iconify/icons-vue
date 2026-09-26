<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ykcszfbtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-checkov" /></template>
<style>
.ykcszfbtw {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M22.41 11.42a6 6 0 0 0-1.48-1.4a7 7 0 0 0-1.75-.87a7 7 0 0 0-1.91-.26a5.5 5.5 0 0 0-2.62.61a6 6 0 0 0-2.1 1.57a7 7 0 0 0-1.48 2.36a10 10 0 0 0-.52 3.14a6.8 6.8 0 0 0 1.92 4.71c.6.6 1.3 1.13 2.09 1.4a6.75 6.75 0 0 0 7.68-1.75a7 7 0 0 0 1.04-1.66l4.98 4.97a14 14 0 0 1-4.8 4.28a12 12 0 0 1-6.2 1.48q-2.74 0-5.23-1.05A13.8 13.8 0 0 1 4.8 21.8q-1.05-2.49-1.05-5.23c0-1.92.35-3.84 1.05-5.67c.7-1.75 1.66-3.23 2.88-4.63c1.22-1.3 2.7-2.35 4.27-3.14A12 12 0 0 1 17.18 2q1.68.02 3.23.44a12 12 0 0 1 5.67 3.22a11 11 0 0 1 2.09 2.7l-4.97 4.98c0-.79-.35-1.4-.79-1.92");
}

</style>
