<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tz9210w4s"/><path class="jagj-lqke"/><path class="lfi66fb9c"/><path class="cogghubum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:e-mail" /></template>
<style>
.cogghubum {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("m35.2 23.6l.6-5.1l-17.5-.1l-2.9 23.9l17 4l.7-5.1l-12.8-2.5l.7-5.5L33.8 35l.6-5.1l-12.9-1.3l.7-5.6z");
}

.jagj-lqke {
  fill: var(--svg-color--cad5dd, #cad5dd);
  d: path("m25.7 39.4l-6.6-10L.6 48.7c.4.9 1.1 1.5 1.9 1.7L53.3 60c1.4.3 2.7-.2 3.7-1.1L35.9 30.4z");
}

.lfi66fb9c {
  fill: var(--svg-color--dfe9ef, #dfe9ef);
  d: path("M59.3 4L7.1 7.5c-.8.1-1.6.6-2.2 1.4l14.3 20.5l6.6 10l10.2-9L62.7 5.5c-.9-1-2.1-1.6-3.4-1.5");
}

.tz9210w4s {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("m.6 48.7l18.5-19.3L4.9 8.9c-.7.9-1.2 2.1-1.3 3.5L0 45.1q-.15 2.1.6 3.6M62.7 5.5L35.9 30.4L57 58.9c1.2-1 2-2.5 2.2-4.3L64 10c.2-1.8-.4-3.5-1.3-4.5");
}

</style>
