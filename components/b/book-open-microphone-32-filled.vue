<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ymsbv49fb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-32-filled" /></template>
<style>
.ymsbv49fb {
  fill: currentColor;
  d: path("M29.5 21a1 1 0 0 1 1 1a6.5 6.5 0 0 1-5.5 6.423V29.5a1 1 0 1 1-2 0v-1.077A6.5 6.5 0 0 1 17.5 22a1 1 0 1 1 2 0a4.5 4.5 0 1 0 9 0a1 1 0 0 1 1-1M12.25 4c1.524 0 2.88.718 3.75 1.834A4.74 4.74 0 0 1 19.75 4h8A2.25 2.25 0 0 1 30 6.25v13.3a2.5 2.5 0 0 0-1.5.159V18.5a4.48 4.48 0 0 0-1-2.828V6.5h-7.75a2.25 2.25 0 0 0-2.25 2.25v10.959A2.5 2.5 0 0 0 16 22c0 2.306.977 4.383 2.538 5.842A4.75 4.75 0 0 1 16 26.166A4.74 4.74 0 0 1 12.25 28h-8A2.25 2.25 0 0 1 2 25.75V6.25A2.25 2.25 0 0 1 4.25 4zM4.5 25.5h7.75a2.25 2.25 0 0 0 2.25-2.25V8.75a2.25 2.25 0 0 0-2.25-2.25H4.5zm19.5-10a3 3 0 0 1 3 3V22a3 3 0 1 1-6 0v-3.5a3 3 0 0 1 3-3");
}

</style>
