<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kq9je2bhh"/><path class="a5pqqpzer"/><path class="zdtyq43mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-jamaica" /></template>
<style>
.a5pqqpzer {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M58 47c5.3-9.2 5.3-20.7 0-29.9L38.6 32zM6 17C.7 26.3.7 37.7 6 47l19.5-15z");
}

.kq9je2bhh {
  fill: var(--svg-color--699635, #699635);
  d: path("M53.1 10.7C41.4-.9 22.5-.9 10.8 10.7L32 27zM10.9 53.3c11.7 11.6 30.6 11.6 42.3 0L32 37z");
}

.zdtyq43mc {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M53.1 10.7L32 27L10.9 10.7C9 12.6 7.3 14.7 6 17l19.4 15L6 47c1.3 2.3 3 4.5 4.9 6.3L32 37l21.1 16.3c1.9-1.9 3.5-4 4.9-6.3L38.6 32L58 17c-1.3-2.3-3-4.4-4.9-6.3");
}

</style>
