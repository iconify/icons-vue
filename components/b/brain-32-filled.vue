<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="er7i73pab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:brain-32-filled" /></template>
<style>
.er7i73pab {
  fill: currentColor;
  d: path("M12.375 2c.975 0 1.88.303 2.625.818V29a4.97 4.97 0 0 1-3 1h-.31a5 5 0 0 1-4.772-3.509l-.169-.544A5.5 5.5 0 0 1 2 20.5V20a6 6 0 0 1 2.858-5.112a5 5 0 0 1 2.935-8.883A4.624 4.624 0 0 1 12.375 2m7.25 0a4.624 4.624 0 0 1 4.582 4.005a5 5 0 0 1 2.935 8.883A6 6 0 0 1 30 20v.5a5.5 5.5 0 0 1-4.749 5.447l-.169.544A5 5 0 0 1 20.31 30H20a4.97 4.97 0 0 1-3-1.001V2.819A4.6 4.6 0 0 1 19.625 2");
}

</style>
