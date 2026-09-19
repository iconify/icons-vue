<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v_lg8hxsb"/><path class="w9d0prbxm"/><path class="r-dgu4j5y"/><path class="k03qbcbbm"/><path class="i4cyxus_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-st-kitts-and-nevis" /></template>
<style>
.i4cyxus_c {
  fill: var(--svg-color--fff, #fff);
  d: path("m22 40.1l4.6.6l-3.5-3.2l1.8-4.3l-4 2.3l-3.5-3.3l1.1 4.7l-3.9 2.2l4.5.7l1.1 4.6zm22-12.7l4.6.6l-3.5-3.3l1.8-4.2l-3.9 2.2l-3.5-3.2l1 4.6l-3.9 2.3l4.6.6l1.1 4.6z");
}

.k03qbcbbm {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M19.1 59.1c8.6 4.1 19 4 27.9-1.1s14.1-14.1 14.9-23.6z");
}

.r-dgu4j5y {
  fill: var(--svg-color--699635, #699635);
  d: path("M44.9 4.9C36.3.8 25.9.9 17 6S2.9 20.1 2.1 29.6z");
}

.v_lg8hxsb {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M6 47c1.9 3.4 4.4 6.2 7.3 8.5l48.4-27.9C61.1 24 59.9 20.4 58 17s-4.4-6.2-7.3-8.5L2.3 36.4C2.9 40.1 4.1 43.6 6 47");
}

.w9d0prbxm {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("m19.1 59.1l42.8-24.7c.2-2.3.1-4.5-.2-6.8L13.3 55.5c1.8 1.4 3.8 2.6 5.8 3.6M2.3 36.4L50.7 8.5c-1.8-1.4-3.7-2.6-5.8-3.6L2.1 29.6c-.2 2.3-.1 4.6.2 6.8");
}

</style>
