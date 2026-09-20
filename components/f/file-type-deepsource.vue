<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jtpuy1bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-deepsource" /></template>
<style>
.jtpuy1bow {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M13.87 2q4.35 0 7.48 1.8q3.14 1.75 4.84 4.93Q27.9 11.89 27.9 16c0 4.11-.57 5.16-1.7 7.27a12.5 12.5 0 0 1-4.85 4.93a15 15 0 0 1-7.48 1.8H4.1V2zM8.86 24.4H19.8c.75 0 1.38-.76 1.38-1.68s-.63-1.68-1.38-1.68H8.86zm0-10.08v3.36h5.95c.73 0 1.33-.76 1.33-1.68s-.6-1.68-1.33-1.68zm0-3.36h9.21c.78 0 1.43-.76 1.43-1.68s-.65-1.68-1.43-1.68H8.86z");
}

</style>
