<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="i43pbtgxu"/><path class="ykwb9xbol"/><path class="m5ry2-b3e"/><path class="xtn1_zhmg"/><path class="igm0eob1f"/><path class="y97okkbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-south-sudan" /></template>
<style>
.i43pbtgxu {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M32 2C19.3 2 8.5 9.9 4.1 21h55.8C55.5 9.9 44.7 2 32 2");
}

.igm0eob1f {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M10.8 10.8C5.4 16.2 2 23.7 2 32s3.4 15.8 8.8 21.2L32 32z");
}

.m5ry2-b3e {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M62 32c0-3.1-.5-6.2-1.4-9H3.4C2.5 25.8 2 28.9 2 32s.5 6.2 1.4 9h57.2c.9-2.8 1.4-5.9 1.4-9");
}

.xtn1_zhmg {
  fill: var(--svg-color--fff, #fff);
  d: path("M60.3 22c-.1-.3-.3-.7-.4-1H4.1c-.1.3-.3.7-.4 1s-.2.7-.3 1h57.2c-.1-.3-.2-.7-.3-1M3.7 42c.1.3.3.7.4 1h55.8c.1-.3.3-.7.4-1s.2-.7.3-1H3.4c.1.3.2.7.3 1");
}

.y97okkbjr {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m16.8 31l3.2-4.2l-5.2 1.6l-3.3-4.2v5.2L6.4 31l5.1 1.6v5.2l3.3-4.2l5.2 1.6z");
}

.ykwb9xbol {
  fill: var(--svg-color--699635, #699635);
  d: path("M32 62c12.7 0 23.5-7.9 27.9-19H4.1C8.5 54.1 19.3 62 32 62");
}

</style>
