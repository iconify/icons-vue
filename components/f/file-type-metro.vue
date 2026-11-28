<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sajls1knf"/><path class="zf2kqpb3s"/><path class="dynustb8j"/><path class="bvmeo0b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-metro" /></template>
<style>
.bvmeo0b-x {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.67 21.24h-2.28V12.9l-7.8 4.4a1.13 1.05 0 0 1-1.18 0L7.6 12.9v8.33H5.33v-10.2a1.14 1.05 0 0 1 1.73-.89L16 15.17l8.94-5.03a1.14 1.05 0 0 1 1.73.9Z");
}

.dynustb8j {
  fill: var(--svg-color--ef4242, #ef4242);
  d: path("M16 24.89a1.27 1.18 0 0 1-.64-.16l-9.54-5.1a1.28 1.18 0 0 1-.64-1.02V8.4a1.28 1.18 0 0 1 1.96-1L16 12.39l8.87-4.99a1.28 1.18 0 0 1 1.94 1.01v10.2a1.27 1.18 0 0 1-.64 1.02l-9.55 5.1a1.29 1.2 0 0 1-.63.16m-8.26-6.97L16 22.34l8.27-4.42v-7.4l-7.6 4.27a1.27 1.18 0 0 1-1.32 0l-7.6-4.27Z");
}

.sajls1knf {
  fill: var(--svg-color--ef4242, #ef4242);
  d: path("M2.27 11.08a4.6 4.6 0 0 1 2.27-3.65l9.18-4.91a5.4 5.4 0 0 1 4.55 0l9.19 4.91a4.6 4.6 0 0 1 2.27 3.64v9.83a4.6 4.6 0 0 1-2.27 3.64l-9.2 4.92a5.4 5.4 0 0 1-4.53 0l-9.2-4.92a4.6 4.6 0 0 1-2.26-3.64Z");
}

.zf2kqpb3s {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 27.23a2.14 1.98 0 0 1-1.06-.25l-8.55-4.57a2.22 2.05 0 0 1-1.06-1.7v-9.14a2.22 2.05 0 0 1 1.06-1.7l8.55-4.57a2.26 2.09 0 0 1 2.11 0l8.55 4.57a2.21 2.05 0 0 1 1.06 1.7v9.14a2.21 2.05 0 0 1-1.06 1.7l-8.55 4.57a2.13 1.97 0 0 1-1.05.25m-8.4-6.6l8.4 4.49l8.4-4.49v-8.98L16 7.15l-8.4 4.5Z");
}

</style>
