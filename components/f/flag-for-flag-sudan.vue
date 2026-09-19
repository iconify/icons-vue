<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ow_ujb5-w"/><path class="vlp_y8gxh"/><path class="uuao_2bop"/><path class="gu95n8b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-sudan" /></template>
<style>
.gu95n8b2t {
  fill: var(--svg-color--699635, #699635);
  d: path("M10.8 10.8C5.4 16.2 2 23.7 2 32s3.4 15.8 8.8 21.2L32 32z");
}

.ow_ujb5-w {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M60 42c-5.5 0-10-4.5-10-10H10.8v21.2C16.2 58.6 23.7 62 32 62c13.1 0 24.2-8.4 28.3-20z");
}

.uuao_2bop {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M60.3 22H10.8v20h49.5c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10");
}

.vlp_y8gxh {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M60 22h.3C56.2 10.4 45.1 2 32 2c-8.3 0-15.8 3.4-21.2 8.8V32H50c0-5.5 4.5-10 10-10");
}

</style>
