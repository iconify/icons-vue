<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zsvml1bdm"/><path class="tq7q20m4t"/><path class="dwgselgvw"/><path class="cqpp88_cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-djibouti" /></template>
<style>
.cqpp88_cb {
  fill: var(--svg-color--c94747, #c94747);
  d: path("m14 35.7l4.3 3.3l-1.6-5.3l4.3-3.5h-5.3L14 25l-1.6 5.2H7l4.3 3.5L9.7 39z");
}

.dwgselgvw {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M11 10.6C5.4 16 2 23.6 2 32s3.4 16 9 21.4L32.4 32z");
}

.tq7q20m4t {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M11 32h51C62 15.4 48.6 2 32 2c-8.2 0-15.6 3.3-21 8.6z");
}

.zsvml1bdm {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M11 32v21.4c5.4 5.3 12.8 8.6 21 8.6c16.6 0 30-13.4 30-30z");
}

</style>
