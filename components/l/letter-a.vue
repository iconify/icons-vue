<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="key3jebrh"/><path class="n-wyo_bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-a" /></template>
<style>
.key3jebrh {
  fill: currentColor;
  d: path("M28.216 35.543h7.431l-3.666-11.418z");
}

.n-wyo_bsn {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.431 2 32s13.432 30 30 30s30-13.432 30-30C62 15.431 48.568 2 32 2m7.167 44.508l-1.914-5.965H26.567L24.6 46.508h-6.342l10.358-29.016h6.859l10.266 29.016z");
}

</style>
