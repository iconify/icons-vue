<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jqi42kbfl"/><path class="qiu5dbboa"/><path class="r-x64p1iy"/><path class="jggfy0bhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-bosnia-and-herzegovina" /></template>
<style>
.jggfy0bhz {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.9 21l2.4 1.8l-.9-3l2.4-1.8h-3l-.9-3l-.9 3H7l2.4 1.8l-.9 3zm6.8 6.8l2.5 1.9l-1-3l2.5-1.9h-3l-1-3l-.9 3h-3l2.4 1.9l-.9 3zm6.9 6.9l2.4 1.8l-.9-3l2.4-1.8l-3-.1l-.9-2.9l-.9 2.9l-3 .1l2.4 1.8l-.9 3zm6.8 6.8l2.4 1.8l-.9-3l2.4-1.8h-3l-.9-3l-.9 3h-3l2.4 1.8l-.9 3zm6.9 6.8l2.4 1.9l-.9-3l2.4-1.9h-3l-.9-3l-1 3h-3l2.5 1.9l-1 3zm6.8 6.9l2.4 1.8l-.9-3l2.4-1.8h-3l-.9-3l-.9 3h-3l2.4 1.8l-.9 3z");
}

.jqi42kbfl {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M10.8 53.2c11.7 11.7 30.7 11.7 42.4 0L10.8 10.8C-.9 22.5-.9 41.5 10.8 53.2");
}

.qiu5dbboa {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m10.8 10.8l42.4 42.4V10.8C41.5-.9 22.5-.9 10.8 10.8");
}

.r-x64p1iy {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M53.2 10.8v42.4c11.7-11.7 11.7-30.7 0-42.4");
}

</style>
