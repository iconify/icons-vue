<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="puyt1dxjs"/><path class="ik_244bja"/><path class="kwnb8lq5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-burkina-faso" /></template>
<style>
.ik_244bja {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2C15.4 2 2 15.4 2 32h60C62 15.4 48.6 2 32 2");
}

.kwnb8lq5l {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m32 36.8l5.6 4.2l-2.1-6.9l5.5-4.2h-6.9L32 23l-2.1 6.9H23l5.5 4.2l-2.1 6.9z");
}

.puyt1dxjs {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M32 62c16.6 0 30-13.4 30-30H2c0 16.6 13.4 30 30 30");
}

</style>
