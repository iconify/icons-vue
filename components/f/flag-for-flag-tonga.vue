<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="drgl8-b0g"/><path class="vcf5u8b2i"/><path class="gdux1aces"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-tonga" /></template>
<style>
.drgl8-b0g {
  fill: var(--svg-color--c10000, #c10000);
  d: path("M32 5H15v13H0v9a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.gdux1aces {
  fill: var(--svg-color--c10000, #c10000);
  d: path("M9 7H6v3H3v3h3v3h3v-3h3v-3H9z");
}

.vcf5u8b2i {
  fill: var(--svg-color--eeeded, #eeeded);
  d: path("M15 5H4a4 4 0 0 0-4 4v9h15zm-3 8H9v3H6v-3H3v-3h3V7h3v3h3z");
}

</style>
