<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy-naub4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension-outline-sharp" /></template>
<style>
.wy-naub4s {
  fill: currentColor;
  d: path("M5 19.116h13.116v-4.677l.72-.243q.516-.142.84-.627T20 12.442q0-.655-.324-1.133t-.84-.64l-.72-.236V5.769h-4.57l-.115-.853q-.114-.743-.632-1.272t-1.241-.528q-.726 0-1.246.528q-.52.529-.633 1.272l-.116.853H5V8.65q1.189.333 2.008 1.397t.819 2.401q0 1.36-.81 2.429q-.81 1.07-2.017 1.363zm-1 1V15.45q1.2-.077 2.014-.916t.813-2.092q0-1.13-.823-2.005T4 9.416V4.768h4.685q.155-1.121.957-1.887t1.924-.766q1.1 0 1.9.762q.8.763.965 1.891h4.685v4.947q.842.257 1.363 1.011T21 12.442q0 .93-.521 1.674t-1.363 1.053v4.947zm8.5-7.674");
}

</style>
