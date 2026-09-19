<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="go8urvbqf"/><path class="mzdxiu87t"/><path class="lnw659yis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-ireland" /></template>
<style>
.go8urvbqf {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M1.8 32c0 13.1 8.4 24.2 20 28.3V3.7C10.1 7.8 1.8 18.9 1.8 32");
}

.lnw659yis {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.8 60.3c3.1 1.1 6.5 1.7 10 1.7s6.9-.6 10-1.7V3.7C38.6 2.6 35.3 2 31.8 2s-6.9.6-10 1.7z");
}

.mzdxiu87t {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M61.8 32c0-13.1-8.4-24.2-20-28.3v56.6c11.6-4.1 20-15.2 20-28.3");
}

</style>
