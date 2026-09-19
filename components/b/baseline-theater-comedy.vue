<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by3w8ccrj"/><path class="rb_fb1-7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-theater-comedy" /></template>
<style>
.by3w8ccrj {
  fill: currentColor;
  d: path("M2 16.5C2 19.54 4.46 22 7.5 22s5.5-2.46 5.5-5.5V10H2zm5.5 2C6.12 18.5 5 17.83 5 17h5c0 .83-1.12 1.5-2.5 1.5M10 13c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1m-5 0c.55 0 1 .45 1 1s-.45 1-1 1s-1-.45-1-1s.45-1 1-1");
}

.rb_fb1-7e {
  fill: currentColor;
  d: path("M11 3v6h3v2.5c0-.83 1.12-1.5 2.5-1.5s2.5.67 2.5 1.5h-5v2.89c.75.38 1.6.61 2.5.61c3.04 0 5.5-2.46 5.5-5.5V3zm3 5.08c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1c0 .56-.45 1-1 1m5 0c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1c0 .56-.45 1-1 1");
}

</style>
