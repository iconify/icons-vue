<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="omn2hm37i"/><path class="xjd6rtn_o"/><path class="amboebc1m"/><path class="n6i54ib5y"/><path class="b1ubl_b4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-namibia" /></template>
<style>
.amboebc1m {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M58 17c-1.4-2.4-3.1-4.5-5-6.4L3 39.5q1.05 3.9 3 7.5c1.4 2.4 3.1 4.5 5 6.4l50-28.9q-.9-3.9-3-7.5");
}

.b1ubl_b4j {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m23.2 13.5l2.3-2.3l-3.1.9l.9-3.1l-2.3 2.3l-.8-3.2l-.8 3.2L17.1 9l.9 3.1l-3.2-.9l2.4 2.3l-3.2.8l3.2.8l-2.4 2.3l3.2-.9l-.9 3.2l2.3-2.4l.8 3.2l.8-3.2l2.3 2.4l-.9-3.2l3.1.9l-2.3-2.3l3.2-.8z");
}

.n6i54ib5y {
  fill: var(--svg-color--fff, #fff);
  d: path("M61.5 26.5c-.1-.7-.3-1.4-.5-2L11 53.4c.5.5 1 1 1.5 1.4c.5.5 1.1.9 1.7 1.3l47.6-27.5zm-10-17.3c-.5-.5-1.1-.9-1.7-1.3L2.2 35.3l.3 2.1c.1.7.3 1.4.5 2l50-28.8c-.5-.5-1-1-1.5-1.4");
}

.omn2hm37i {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M17 6C6.3 12.2.9 23.9 2.2 35.3L49.8 7.9C40.5 1 27.6-.1 17 6m8.5 11.4l-3.2-.9l.9 3.2l-2.2-2.4l-.8 3.2l-.8-3.2l-2.3 2.4l.9-3.2l-3.2.9l2.4-2.3l-3.2-.8l3.2-.8l-2.4-2.3l3.2.9l-.9-3.2l2.3 2.4l.8-3.2l.8 3.2l2.3-2.4l-.9 3.2l3.2-.9l-2.4 2.3l3.2.8l-3.2.8z");
}

.xjd6rtn_o {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M14.2 56.1c9.3 6.9 22.2 8 32.8 1.8c10.7-6.2 16.1-17.8 14.8-29.3z");
}

</style>
