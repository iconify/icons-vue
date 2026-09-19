<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ng6v9lbft"/><path class="awlm-8h3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:egg" /></template>
<style>
.awlm-8h3y {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M53.6 29.8c-2-14.2-9.5-23.3-16.4-26.5c4.7 4.7 8.9 12.1 10.2 22.1c2.5 18-5.4 32.2-21.6 32.2c-3.5 0-6.6-.7-9.2-1.9c3.7 4 8.9 6.3 15.4 6.3c16.1 0 24-14.2 21.6-32.2");
  opacity: var(--svg-opacity--0-33, 0.33);
}

.ng6v9lbft {
  fill: var(--svg-color--ffc294, #ffc294);
  d: path("M53.6 29.8C51.1 11.8 39.7 2 32 2s-19.1 9.8-21.6 27.8C8 47.8 15.9 62 32 62s24-14.2 21.6-32.2");
}

</style>
