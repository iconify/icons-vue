<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykv9rg6fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:communication-24-regular" /></template>
<style>
.ykv9rg6fs {
  fill: currentColor;
  d: path("M12 4.5a8.5 8.5 0 0 0-6.016 14.505a.75.75 0 0 1-1.061 1.06A9.97 9.97 0 0 1 2 13C2 7.477 6.477 3 12 3s10 4.477 10 10a9.97 9.97 0 0 1-2.923 7.065a.75.75 0 0 1-1.061-1.06A8.5 8.5 0 0 0 12 4.5M12 8a5 5 0 0 0-3.534 8.537a.75.75 0 0 1-1.06 1.061a6.5 6.5 0 1 1 9.188 0a.75.75 0 0 1-1.06-1.06A5 5 0 0 0 12 8m0 2.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M11 13a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

</style>
