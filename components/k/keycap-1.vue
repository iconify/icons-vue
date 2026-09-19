<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="if_qk_b0g"/><path class="bckr3gb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:keycap-1" /></template>
<style>
.bckr3gb6q {
  fill: currentColor;
  d: path("M38 45h-6.107V21.979Q28.545 25.108 24 26.608v-5.543q2.391-.783 5.195-2.967T33.043 13H38z");
}

.if_qk_b0g {
  fill: currentColor;
  d: path("M52 2H12C6.479 2 2 6.477 2 12v40c0 5.523 4.479 10 10 10h40c5.523 0 10-4.477 10-10V12c0-5.523-4.477-10-10-10m5 43.666A8.33 8.33 0 0 1 48.668 54H15.334A8.334 8.334 0 0 1 7 45.666V12.334A8.334 8.334 0 0 1 15.334 4h33.334A8.33 8.33 0 0 1 57 12.334z");
}

</style>
