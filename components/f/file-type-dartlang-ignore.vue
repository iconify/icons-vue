<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="myjauys_t"/><path class="qwo1d03av"/><path class="uaiq-5b5b"/><path class="ev8xw9iki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-dartlang-ignore" /></template>
<style>
.ev8xw9iki {
  fill: var(--svg-color--91d8a1, #91d8a1);
  d: path("M7.26 7.41L16 16.18l10.1 10.09l-.74 3.84H14l-4-4.05a6.54 6.54 0 0 1-1.61-3.63Z");
}

.myjauys_t {
  fill: var(--svg-color--91d8a1, #91d8a1);
  d: path("M16.74 2a1.33 1.33 0 0 0-.92.37l-8.59 5L15.79 16l10.3 10.3l2-3.53L21 5.73l-3.3-3.3a1.3 1.3 0 0 0-.96-.43");
}

.qwo1d03av {
  fill: var(--svg-color--368f49, #368f49);
  d: path("m7.25 7.35l-5 8.58a1.34 1.34 0 0 0-.38.92a1.3 1.3 0 0 0 .39.93L6.4 21.9l16.08 6.33l3.64-2l-.1-.1L15.91 16Z");
}

.uaiq-5b5b {
  fill: var(--svg-color--368f49, #368f49);
  d: path("M7.19 7.36L16 16.14l10.09 10.1l3.84-.74V14.14l-4-4a6.48 6.48 0 0 0-3.63-1.62Z");
}

</style>
