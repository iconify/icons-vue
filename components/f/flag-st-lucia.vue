<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="s_f0pqh0m"/><path class="dhuxhxbvf"/><path class="nlcwnjb_o"/><path class="apmp7gn8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-st-lucia" /></template>
<style>
.apmp7gn8y {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("m18 18l-6.321 7.838l-2.346 2.909h17.334l-2.346-2.909z");
}

.dhuxhxbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.333 28.747l2.346-2.909L18 10.2l6.321 15.638l2.346 2.909L18 7.34z");
}

.nlcwnjb_o {
  d: path("M24.321 25.838L18 10.2l-6.321 15.638L18 18z");
}

.s_f0pqh0m {
  fill: var(--svg-color--6cf, #6cf);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

</style>
