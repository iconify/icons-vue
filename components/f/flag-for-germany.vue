<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hb4hm1bhu"/><path class="av48-ymix"/><path class="ffmgmkbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-germany" /></template>
<style>
.av48-ymix {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M31.9 62c13.1 0 24.2-8.3 28.3-20H3.6c4.1 11.7 15.2 20 28.3 20");
}

.ffmgmkbsf {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M3.6 22c-1.1 3.1-1.7 6.5-1.7 10s.6 6.9 1.7 10h56.6c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10z");
}

.hb4hm1bhu {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M31.9 2C18.8 2 7.7 10.4 3.6 22h56.6C56.1 10.4 45 2 31.9 2");
}

</style>
