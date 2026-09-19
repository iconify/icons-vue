<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="iw4_bhbpc"/><path class="r140ez8zl"/><g class="hq2-vcghy"><path class="wktn2tbis"/><path class="uysxcbbtt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-algeria" /></template>
<style>
.hq2-vcghy {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
}

.iw4_bhbpc {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M62 32C62 15.4 48.6 2 32 2v60c16.6 0 30-13.4 30-30");
}

.r140ez8zl {
  fill: var(--svg-color--699635, #699635);
  d: path("M2 32c0 16.6 13.4 30 30 30V2C15.4 2 2 15.4 2 32");
}

.uysxcbbtt {
  d: path("M37.2 44c-6.6 0-11.9-5.4-11.9-12s5.3-12 11.9-12c2.5 0 4.8.8 6.8 2.1C41.3 19 37.3 17 32.8 17C24.6 17 18 23.7 18 32s6.6 15 14.8 15c4.5 0 8.5-2 11.2-5.1c-1.9 1.3-4.2 2.1-6.8 2.1");
}

.wktn2tbis {
  d: path("m40.7 39l-.1-5.4L46 32l-5.4-1.6l.1-5.4l-3.3 4.3l-5.4-1.6l3.3 4.3l-3.3 4.3l5.4-1.6z");
}

</style>
