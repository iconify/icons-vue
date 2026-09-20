<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f9rjpcc3b"/><path class="h2jstwvvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-yaml-official" /></template>
<style>
.f9rjpcc3b {
  fill: var(--svg-color--cb171e, #cb171e);
  d: path("M20.06 12.73H14.5l-1.13 2.73H10.9l5.22-12.3h2.52l5 12.3H21zm-.92-2.46l-1.71-4.51l-1.9 4.51z");
}

.h2jstwvvh {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M30 28.82v-2.57h-6.36v-9.44H21v12zm-15.87-2.68l2.8-5.78v8.5h2.48V16.82H16l-3 5.46l-2.86-5.46H6.8v12.06h2.58v-8.32l2.71 5.6zM2 3.14h3.46L8.5 7.97l3.07-4.85h3.31l-5.02 7.53v4.77H6.8v-4.77z");
}

</style>
