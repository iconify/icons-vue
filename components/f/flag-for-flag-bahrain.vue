<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bgkequbdp"/><path class="wrc8j3b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-bahrain" /></template>
<style>
.bgkequbdp {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M26.8 61.5L36 56l-10-6l10-6l-10-6l10-6l-10-6l10-6l-10-6l10-6l-9.2-5.5C12.7 4.9 2 17.2 2 32s10.7 27.1 24.8 29.5");
}

.wrc8j3b8m {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M32 2c-1.8 0-3.5.2-5.2.5L36 8l-10 6l10 6l-10 6l10 6l-10 6l10 6l-10 6l10 6l-9.2 5.5c1.7.3 3.4.5 5.2.5c16.6 0 30-13.4 30-30S48.6 2 32 2");
}

</style>
