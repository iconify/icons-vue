<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="xbdyagbrm"/><path class="zqiu_obsb"/><path class="g-3aqbbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-czechia" /></template>
<style>
.g-3aqbbwd {
  fill: var(--svg-color--11457e, #11457e);
  d: path("M1.383 29.973L17.5 18L1.354 6.006A4 4 0 0 0 0 9v17.5c0 1.48.537 2.683 1.383 3.473");
}

.xbdyagbrm {
  fill: var(--svg-color--d7141a, #d7141a);
  d: path("M1.383 29.973A3.8 3.8 0 0 0 4 31h28c2.209 0 4-1.791 4-4.5V18H17.5z");
}

.zqiu_obsb {
  fill: var(--svg-color--eee, #eee);
  d: path("M32 5H4a3.98 3.98 0 0 0-2.646 1.006L17.5 18H36V9a4 4 0 0 0-4-4");
}

</style>
