<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ribc8xb-p"/><path class="fnn7mnb8u"/><path class="kmh2g8oea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:love-letter" /></template>
<style>
.fnn7mnb8u {
  fill: var(--svg-color--dae4ea, #dae4ea);
  d: path("M35.3 30.7L60.2 8.6c-.8-.9-1.9-1.4-3.2-1.3L8.5 10.5c-.7 0-1.5.5-2 1.2l13.2 18.2L2.6 47c.4.8 1 1.3 1.7 1.5L51.5 57c1.3.2 2.5-.1 3.5-.9z");
}

.kmh2g8oea {
  fill: var(--svg-color--f46767, #f46767);
  d: path("M39.3 22.8c-1.7-8.9-10.4-4.8-11.6-.6c-.5-4.5-7.4-7.6-10.3.3c-3.2 8.6 7.4 17.6 8.2 19.1c1-.9 15.6-8.9 13.7-18.8");
}

.ribc8xb-p {
  fill: var(--svg-color--c4ced6, #c4ced6);
  d: path("m2.6 47l17.2-17.1L6.5 11.7c-.6.8-1.1 1.9-1.2 3.1L2 43.8c-.1 1.2.1 2.3.6 3.2M60.2 8.6L35.3 30.7L54.9 56c1.1-.9 1.8-2.2 2-3.8l4.4-39.5c.3-1.7-.2-3.1-1.1-4.1");
}

</style>
