<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ark2mpgmr"/><path class="em9yh6-cp"/><path class="kezz0ktoq"/><path class="qt1d1wbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-djibouti" /></template>
<style>
.ark2mpgmr {
  fill: var(--svg-color--6ab2e7, #6AB2E7);
  d: path("M32 5H4a3.98 3.98 0 0 0-2.646 1.006L17.5 18H36V9a4 4 0 0 0-4-4z");
}

.em9yh6-cp {
  fill: var(--svg-color--12ad2b, #12AD2B);
  d: path("M32 31H4a3.98 3.98 0 0 1-2.646-1.006L17.5 18H36v9a4 4 0 0 1-4 4z");
}

.kezz0ktoq {
  fill: var(--svg-color--eee, #EEE);
  d: path("M1.383 29.973L17.5 18L1.354 6.006A3.985 3.985 0 0 0 0 9v17.5c0 1.48.537 2.683 1.383 3.473z");
}

.qt1d1wbwm {
  fill: var(--svg-color--d7141a, #D7141A);
  d: path("M6.5 14.5l.826 2.543H10l-2.163 1.572l.826 2.543L6.5 19.586l-2.163 1.572l.826-2.543L3 17.043h2.674L6.5 14.5z");
}

</style>
