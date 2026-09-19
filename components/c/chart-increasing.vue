<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="p56r-9gea"/><path class="aca4s0bmt"/><path class="tw6iecbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:chart-increasing" /></template>
<style>
.aca4s0bmt {
  fill: var(--svg-color--52c18e, #52c18e);
  d: path("M58.7 5.3h-5.6L37.3 25.5l-9.6-11.2L0 54.5V64h6.4l22.2-32.3l9.2 10.6l20.9-26.8z");
}

.p56r-9gea {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h64v64H0z");
}

.tw6iecbnq {
  fill: var(--svg-color--d0d5d8, #d0d5d8);
  d: path("M64 0H0v50.7l3-4.3h-.9V33.1h10l1.5-2.1H2.1V17.6h13.3v10.7l2.1-3.1v-7.6h5.2l1.5-2.1h-6.7V2.1h13.3v12.7l2.4 2.8h7.5l1.7-2.1H33V2.1h13.3v8.3l2.1-2.7V2.1h13.3v13.3h-1.1v.8l-1 1.3h2.1v13.3H49.3l-2.9 3.8v11.7H33.1V40L31 37.5v8.7h-9.8l-1.5 2.1H31v13.3H17.6V51.5l-2.1 3.1v7.3h-5L9 64h55zM15.5 15.5H2.1V2.1h13.3c.1 0 .1 13.4.1 13.4m30.9 46.4H33.1V48.5h13.3zm15.5 0H48.5V48.5h13.3v13.4zm0-15.5H48.5V33.1h13.3v13.3z");
}

</style>
