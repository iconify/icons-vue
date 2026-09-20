<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o6c-54b0f"/><path class="l9ig49-tt"/><path class="eyj23hb3q"/><path class="ex-719bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-djibouti" /></template>
<style>
.ex-719bar {
  fill: var(--svg-color--d7141a, #d7141a);
  d: path("m6.5 14.5l.826 2.543H10l-2.163 1.572l.826 2.543L6.5 19.586l-2.163 1.572l.826-2.543L3 17.043h2.674z");
}

.eyj23hb3q {
  fill: var(--svg-color--eee, #eee);
  d: path("M1.383 29.973L17.5 18L1.354 6.006A4 4 0 0 0 0 9v17.5c0 1.48.537 2.683 1.383 3.473");
}

.l9ig49-tt {
  fill: var(--svg-color--12ad2b, #12ad2b);
  d: path("M32 31H4a3.98 3.98 0 0 1-2.646-1.006L17.5 18H36v9a4 4 0 0 1-4 4");
}

.o6c-54b0f {
  fill: var(--svg-color--6ab2e7, #6ab2e7);
  d: path("M32 5H4a3.98 3.98 0 0 0-2.646 1.006L17.5 18H36V9a4 4 0 0 0-4-4");
}

</style>
