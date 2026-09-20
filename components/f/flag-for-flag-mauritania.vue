<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="p74sq-bwz"/><path class="m17n_709x"/><path class="bv99hveaj"/><path class="pnh6zpbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-mauritania" /></template>
<style>
.bv99hveaj {
  fill: var(--svg-color--ffc514, #FFC514);
  d: path("M14.936 12.664l1.894 1.375l-.722 2.221l-.002.005l.007-.005L18 14.889l1.887 1.371l.006.005l-.001-.005l-.722-2.221l1.894-1.375h-2.341L18 10.437l-.723 2.227z");
}

.m17n_709x {
  fill: var(--svg-color--0f6433, #0F6433);
  d: path("M0 9v18h36V9z");
}

.p74sq-bwz {
  fill: var(--svg-color--ce2540, #CE2540);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4z");
}

.pnh6zpbjj {
  fill: var(--svg-color--ffc514, #FFC514);
  d: path("M26.1 13.641c-.019 4.458-3.638 8.067-8.1 8.067s-8.081-3.609-8.1-8.067a8.373 8.373 0 0 0-.294 2.173a8.395 8.395 0 1 0 16.79 0a8.417 8.417 0 0 0-.296-2.173z");
}

</style>
