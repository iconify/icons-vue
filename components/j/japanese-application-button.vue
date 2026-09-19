<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="etf6yrbqc"/><path class="nukl79b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:japanese-application-button" /></template>
<style>
.etf6yrbqc {
  fill: var(--svg-color--f6921e, #f6921e);
  d: path("M63.974 57.076a6.89 6.89 0 0 1-6.894 6.893H6.892A6.89 6.89 0 0 1 0 57.076V6.893A6.89 6.89 0 0 1 6.892 0H57.08a6.893 6.893 0 0 1 6.894 6.893z");
}

.nukl79b1f {
  fill: var(--svg-color--fff, #fff);
  d: path("M54.1 12.334a.33.33 0 0 0-.098-.246q-.006-.008-.01-.002a.34.34 0 0 0-.248-.097H34.312V4.526a.367.367 0 0 0-.362-.363h-4.605a.367.367 0 0 0-.363.363v7.464H10.237a.367.367 0 0 0-.363.363v30.618c0 .198.165.364.363.364H28.98v14.134c0 .198.165.363.363.363h4.605a.366.366 0 0 0 .362-.363v-14.13h19.433a.33.33 0 0 0 .257-.108a.34.34 0 0 0 .099-.248V12.365zm-19.797 25.65v-7.786H48.77v7.786zm0-12.89v-7.787H48.77v7.787zm-19.11 12.89v-7.786h13.776v7.786zm0-12.89v-7.787h13.776v7.787z");
}

</style>
