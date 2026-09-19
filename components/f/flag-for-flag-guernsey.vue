<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h25i5aczl"/><path class="bd0gci59y"/><path class="gs254fblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-guernsey" /></template>
<style>
.bd0gci59y {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M38 26V2.6Q35.15 2 32 2c-3.15 0-4.1.2-6 .6V26H2.6Q2 28.85 2 32c0 3.15.2 4.1.6 6H26v23.4q2.85.6 6 .6c3.15 0 4.1-.2 6-.6V38h23.4q.6-2.85.6-6c0-3.15-.2-4.1-.6-6z");
}

.gs254fblc {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M52 29.5H34.5V12L37 9.5H27l2.5 2.5v17.5H12L9.5 27v10l2.5-2.5h17.5V52L27 54.5h10L34.5 52V34.5H52l2.5 2.5V27z");
}

.h25i5aczl {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M38 2.6H26C14.3 5 5 14.2 2.6 26v12C5 49.8 14.3 59 26 61.4h12C49.8 59 59 49.7 61.4 38V26C59 14.2 49.7 5 38 2.6");
}

</style>
