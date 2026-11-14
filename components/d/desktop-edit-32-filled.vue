<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q0cx6occw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-edit-32-filled" /></template>
<style>
.q0cx6occw {
  fill: currentColor;
  d: path("M15.945 9.934a4.16 4.16 0 0 0-1.073 1.886l-.79 3.051c-.477 1.844 1.199 3.523 3.042 3.048l3.02-.777a4.3 4.3 0 0 0 1.95-1.11L30 8.19v13.56A3.25 3.25 0 0 1 26.75 25h-6.744v2.001h2.998a1 1 0 0 1 0 2H9.012a1 1 0 0 1 0-2h2.998v-2H5.25A3.25 3.25 0 0 1 2 21.75V6.25A3.25 3.25 0 0 1 5.25 3h17.57zM14.01 27.001h3.996v-2H14.01zM25.572 2.35a2.88 2.88 0 0 1 4.144.058a2.88 2.88 0 0 1-.072 4.016l-8.609 8.543c-.351.349-.79.598-1.27.722l-3.019.777a1 1 0 0 1-1.217-1.219l.79-3.051a2.66 2.66 0 0 1 .686-1.205z");
}

</style>
