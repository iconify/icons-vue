<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="vgnv5k5we"/><path class="e2iqnjbvb"/></g><path class="er0v85b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:figma-bold-duotone" /></template>
<style>
.e2iqnjbvb {
  d: path("M14.999 2C16.8399 2 18.3328 3.49221 18.333 5.33301C18.333 7.17396 16.84 8.66699 14.999 8.66699H11.667V15.334H8.33301C6.49226 15.3338 5.00009 13.8408 5 12C5 10.1592 6.49221 8.66717 8.33301 8.66699C6.49221 8.66682 5 7.17385 5 5.33301C5.00018 3.49232 6.49232 2.00018 8.33301 2H14.999Z");
}

.er0v85b1x {
  fill: currentColor;
  d: path("M18.3327 11.9998C18.3327 13.8408 16.8403 15.3332 14.9993 15.3332C13.1584 15.3332 11.666 13.8408 11.666 11.9998C11.666 10.1589 13.1584 8.6665 14.9993 8.6665C16.8403 8.6665 18.3327 10.1589 18.3327 11.9998Z");
}

.vgnv5k5we {
  d: path("M11.667 18.667C11.6669 20.5079 10.1739 22 8.33301 22C6.49226 21.9998 5.00009 20.5078 5 18.667C5 16.8262 6.49221 15.3342 8.33301 15.334H11.667V18.667Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
