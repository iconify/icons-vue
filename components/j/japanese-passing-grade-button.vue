<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u423wop7q"/><path class="e-z-f5n0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:japanese-passing-grade-button" /></template>
<style>
.e-z-f5n0w {
  fill: currentColor;
  d: path("M52 2H12C6.477 2 2 6.478 2 12v40c0 5.523 4.477 10 10 10h40c5.523 0 10-4.477 10-10V12c0-5.522-4.477-10-10-10m-4.018 50H16.018V36.805h31.965V52zM20.85 34.645v-5.14h22.299v5.14zm30.175-1.954S43.111 30.1 32.001 21.162C20.889 30.1 12.975 32.691 12.975 32.691L9.777 26.6C22.031 20.641 32.001 12 32.001 12s9.969 8.641 22.222 14.6z");
}

.u423wop7q {
  fill: currentColor;
  d: path("M22.442 42.242h19.116v4.32H22.442z");
}

</style>
