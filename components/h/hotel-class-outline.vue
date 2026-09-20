<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8451856e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hotel-class-outline" /></template>
<style>
.d8451856e {
  fill: currentColor;
  d: path("m15.508 14.116l3.473-3l1.442.134l-3.746 3.229l1.108 4.887l-1.224-.743zM13.6 8.219l-.973-2.296l.554-1.365l1.588 3.77zm-6.25 8.606l3.15-1.9l3.15 1.925l-.825-3.6l2.775-2.4l-3.65-.325l-1.45-3.4L9.05 10.5l-3.65.325l2.775 2.425zm-1.525 2.098l1.24-5.313l-4.123-3.572l5.431-.47l2.127-5.01l2.127 5.01l5.43.47l-4.123 3.572l1.241 5.313l-4.675-2.821zm4.675-6.442");
}

</style>
