<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="phv2ynbfx"/><path class="n8sjk_zak"/><path class="xg9c6mb2f"/><path class="com1b6byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:incoming-envelope" /></template>
<style>
.com1b6byr {
  fill: var(--svg-color--79d3f7, #79d3f7);
  d: path("M9.2 45c.8 0 1.4.7 1.3 1.5l-.7 6.1c-.1.8-.8 1.4-1.7 1.3L1.8 53C1 52.9.4 52.1.5 51.3l.7-5c.1-.8.9-1.5 1.7-1.5zm2.1-15.3c.8-.1 1.4.5 1.3 1.4l-.8 6.8c-.1.8-.9 1.5-1.7 1.5H1.5c-.8 0-1.4-.7-1.3-1.5l.9-5.9c.1-.8.9-1.5 1.7-1.6zm2.1-16.3c.8-.1 1.4.4 1.3 1.2l-.8 6.9c-.1.8-.9 1.6-1.7 1.7L1.6 24.3C.8 24.4.2 23.8.4 23l1-5.9c.1-.8.9-1.6 1.7-1.7z");
}

.n8sjk_zak {
  fill: var(--svg-color--cad5dd, #cad5dd);
  d: path("m32.5 42.1l-4.8-9.3l-15.4 20.8c.3.8.8 1.4 1.4 1.5L53.6 60c1.1.1 2.1-.4 3-1.4L41 32.3z");
}

.phv2ynbfx {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("m12.3 53.6l15.4-20.8l-10.5-19c-.6.9-1 2.2-1.2 3.6l-4 32.7c-.2 1.4-.1 2.6.3 3.5M63.1 5.2L41 32.3l15.6 26.4c1-1.1 1.7-2.6 1.9-4.5L64 9.7c.2-2-.2-3.5-.9-4.5");
}

.xg9c6mb2f {
  fill: var(--svg-color--dfe9ef, #dfe9ef);
  d: path("M60.5 4.1L19 12.3c-.6.1-1.3.7-1.8 1.6l10.5 19l4.8 9.3l8.4-9.9L63.1 5.2c-.6-.9-1.6-1.4-2.6-1.1");
}

</style>
